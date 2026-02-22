# generator-jhipster-yellowbricks-angular-relativepathresource

A [JHipster](https://www.jhipster.tech/) blueprint that makes the navbar logo path relative in `navbar.scss`.

[![NPM version][npm-image]][npm-url]
[![Generator][github-generator-image]][github-generator-url]
![GitHub Maintained](https://img.shields.io/maintenance/yes/2026)

## JHipster source

- Generator: [`generators/angular`](https://github.com/jhipster/generator-jhipster/tree/main/generators/angular)
- Template: [`navbar.scss.ejs`](https://github.com/jhipster/generator-jhipster/blob/main/generators/angular/templates/src/main/webapp/app/layouts/navbar/navbar.scss.ejs)

## What it does

Patches `src/main/webapp/app/layouts/navbar/navbar.scss` during generation to remove the leading slash from the logo background URL:

```diff
  vertical-align: middle;
- background: url('/content/images/logo-jhipster.png') no-repeat center center;
+ background: url('content/images/logo-jhipster.png') no-repeat center center;
  background-size: contain;
```

This ensures the logo loads correctly when the app is deployed under a non-root context path.

## Prerequisites

- Node.js `^22.18.0 || >=24.11.0`
- JHipster 9

## Installation

```bash
npm install -g generator-jhipster-yellowbricks-angular-relativepathresource
```

## Usage

No configuration is needed. Run JHipster with this blueprint:

```bash
# Standard generator
jhipster --blueprints yellowbricks-angular-relativepathresource

# With JDL
jhipster import-jdl your-app.jdl --blueprints yellowbricks-angular-relativepathresource
```

[npm-image]: https://img.shields.io/npm/v/generator-jhipster-yellowbricks-angular-relativepathresource.svg
[npm-url]: https://npmjs.org/package/generator-jhipster-yellowbricks-angular-relativepathresource
[github-generator-image]: https://github.com/idNoRD/generator-jhipster-yellowbricks-angular-relativepathresource/actions/workflows/generator.yml/badge.svg
[github-generator-url]: https://github.com/idNoRD/generator-jhipster-yellowbricks-angular-relativepathresource/actions/workflows/generator.yml
