# cz-videoamp-conventional-changelog

# Summary

This adapter is used in conjunction with commitizen  (see below) and the cz-conventional-changelog adapter, but is modified for
videoamp so that we include an optional Jira ticket question when a developer does `git cz -a`

## Global Setup and Use

### Install commitizen and this adapter
`npm i -g commitizen @videoamp-private/cz-videoamp-conventional-changelog`

### Create a global ~/.czrc file
`bash
cat ~/.czrc
{ "path": "@videoamp-private/cz-videoamp-conventional-changelog" }
`

## Publishing Info:
If you want to make changes to this adapter, make them in the engine.js and index.js files, then update the version in package.json
and npm publish locally since there is currently no build pipeline


Status:
[![npm version](https://img.shields.io/npm/v/cz-conventional-changelog.svg?style=flat-square)](https://www.npmjs.org/package/cz-conventional-changelog)
[![npm downloads](https://img.shields.io/npm/dm/cz-conventional-changelog.svg?style=flat-square)](http://npm-stat.com/charts.html?package=cz-conventional-changelog&from=2015-08-01)
[![Build Status](https://img.shields.io/travis/commitizen/cz-conventional-changelog.svg?style=flat-square)](https://travis-ci.org/commitizen/cz-conventional-changelog)

Part of the [commitizen](https://github.com/commitizen/cz-cli) family. Prompts for [conventional changelog](https://github.com/conventional-changelog/conventional-changelog) standard.
