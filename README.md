# [future-of-britain-form](https://ig.ft.com/sites/future-of-britain-form)

> Testing Google Form embeds in ig sites

[![Build Status][circle-image]][circle-url] [![Dependency Status][devdeps-image]][devdeps-url]

## Local

```
npm start
```

Build/compile, start a dev server and watches for changes.

# Deploy

1. Write code in a branch.
2. Make a PR. CI will automatically:
    * build and test the branch
    * deploy green builds to the review site
3. Do quick smoke testing of the review build
4. Get a code review. Once you get a thumbs up, merge into master.
5. CI will build, test and deploy a build to Production.


## Uses Starter Kit

This project was scaffolded with [Starter Kit @5c74128](https://github.com/ft-interactive/starter-kit/tree/5c74128).

## Licence
This software is published by the Financial Times under the [MIT licence](http://opensource.org/licenses/MIT).

Please note the MIT licence includes only the software, and does not cover any FT content made available using the software, which is copyright &copy; The Financial Times Limited, all rights reserved. For more information about re-publishing FT content, please contact our [syndication department](http://syndication.ft.com/).

<!-- badge URLs -->
[circle-url]: https://circleci.com/gh/ft-interactive/future-of-britain-form
[circle-image]: https://circleci.com/gh/ft-interactive/future-of-britain-form/tree/master.svg?style=shield

[devdeps-url]: https://david-dm.org/ft-interactive/future-of-britain-form#info=devDependencies
[devdeps-image]: https://img.shields.io/david/dev/ft-interactive/future-of-britain-form.svg?style=flat-square
