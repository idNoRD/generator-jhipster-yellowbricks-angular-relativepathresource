# generator-jhipster-yellowbricks-angular-relativepathresource

Assume the context-path is "/jh"

Template: https://github.com/jhipster/generator-jhipster/blob/main/generators/angular/templates/src/main/webapp/app/layouts/navbar/navbar.scss.ejs

For `src/main/webapp/app/layouts/navbar/navbar.scss`

```diff
  vertical-align: middle;
- background: url('/content/images/logo-jhipster.png') no-repeat center center;
+ background: url('content/images/logo-jhipster.png') no-repeat center center;
  background-size: contain;
```

> JHipster blueprint, yellowbricks-angular-relativepathresource blueprint for JHipster

[![NPM version][npm-image]][npm-url]
[![Generator][github-generator-image]][github-generator-url]
[![Samples][github-samples-image]][github-samples-url]

# Introduction

This is a [JHipster](https://www.jhipster.tech/) blueprint, that is meant to be used in a JHipster application.

# Prerequisites

As this is a [JHipster](https://www.jhipster.tech/) blueprint, we expect you have JHipster basic knowledge:

- [JHipster](https://www.jhipster.tech/)

# Installation

To install or update this blueprint:

```bash
npm install -g generator-jhipster-yellowbricks-angular-relativepathresource
```

# Usage

To use this blueprint, run the below command

````bash
jhipster-yellowbricks-angular-relativepathresource

You can look for updated yellowbricks-angular-relativepathresource blueprint specific options by running

```bash
jhipster-yellowbricks-angular-relativepathresource app --help
````

And looking for `(blueprint option: yellowbricks-angular-relativepathresource)` like

## Pre-release

To use an unreleased version, install it using git.

```bash
npm install -g jhipster/generator-jhipster-yellowbricks-angular-relativepathresource#main
jhipster --blueprints yellowbricks-angular-relativepathresource --skip-jhipster-dependencies
```

[npm-image]: https://img.shields.io/npm/v/generator-jhipster-yellowbricks-angular-relativepathresource.svg
[npm-url]: https://npmjs.org/package/generator-jhipster-yellowbricks-angular-relativepathresource
[github-generator-image]: https://github.com/jhipster/generator-jhipster-yellowbricks-angular-relativepathresource/actions/workflows/generator.yml/badge.svg
[github-generator-url]: https://github.com/jhipster/generator-jhipster-yellowbricks-angular-relativepathresource/actions/workflows/generator.yml
[github-samples-image]: https://github.com/jhipster/generator-jhipster-yellowbricks-angular-relativepathresource/actions/workflows/samples.yml/badge.svg
[github-samples-url]: https://github.com/jhipster/generator-jhipster-yellowbricks-angular-relativepathresource/actions/workflows/samples.yml
