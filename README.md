# Ember CLI Mirage

[![Build Status](https://travis-ci.org/samselikoff/ember-cli-mirage.svg?branch=master)](https://travis-ci.org/samselikoff/ember-cli-mirage)
[![npm version](https://badge.fury.io/js/ember-cli-mirage.svg)](http://badge.fury.io/js/ember-cli-mirage)
[![Ember Observer Score](http://emberobserver.com/badges/ember-cli-mirage.svg)](http://emberobserver.com/addons/ember-cli-mirage)

A client-side server to develop, test and prototype your Ember CLI app.

<http://www.ember-cli-mirage.com/>

----

Are you tired of

- Writing one set of mocks for your tests, and another for development?
- Wiring up tests for each of your apps manually, from scratch?
- Changing lots of files/tests when your API changes?

Ember CLI Mirage may be for you! It lets you create a client-side server using [Pretender](https://github.com/trek/pretender) to help you develop and test your app. By default, it only runs if you're not in production and if you're not proxying to an explicit API server via `ember serve --proxy`.

## Installation

```sh
ember install ember-cli-mirage  # install:addon for Ember CLI < 0.2.3
```

and add `server` to the `predef` section in your `tests/.jshintrc` file.

## Updating

This project is new and the API is subject to change. When updating your project to a newer version of Ember CLI Mirage, please consult [the changelog](/CHANGELOG.md) for any update notes.

## Getting started

Check out the [Docs](http://www.ember-cli-mirage.com/docs/latest/)!

## FAQ

### Known issues

- Pretender doesn't handle other-origin requests (e.g. api.twitter.com)

### Support

Having trouble? Open an issue!
