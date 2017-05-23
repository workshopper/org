# Deployment of workshoppers

This document should help you when deploying new workshopper tutorials [to npm](https://www.npmjs.com/org/workshopper) and on github.

## Current versions and build status

workshopper | NPM | Github | CI |
------------| --- | ------ | -- |
adventure   | [![npm](https://img.shields.io/npm/v/adventure.svg)](https://www.npmjs.com/package/adventure) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/adventure.svg)](https://github.com/workshopper/adventure) | [![Build Status](https://travis-ci.org/workshopper/adventure.svg?branch=master)](https://travis-ci.org/workshopper/adventure)
browserify-adventure | [![npm](https://img.shields.io/npm/v/browserify-adventure.svg)](https://www.npmjs.com/package/browserify-adventure) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/browserify-adventure.svg)](https://github.com/workshopper/browserify-adventure) | [![Build Status](https://travis-ci.org/workshopper/browserify-adventure.svg?branch=master)](https://travis-ci.org/workshopper/browserify-adventure)
goingnative | [![npm](https://img.shields.io/npm/v/goingnative.svg)](https://www.npmjs.com/package/goingnative) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/goingnative.svg)](https://github.com/workshopper/goingnative) | [![Build Status](https://travis-ci.org/workshopper/goingnative.svg?branch=master)](https://travis-ci.org/workshopper/goingnative)
how-to-markdown | [![npm](https://img.shields.io/npm/v/how-to-markdown.svg)](https://www.npmjs.com/package/how-to-markdown) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/how-to-markdown.svg)](https://github.com/workshopper/how-to-markdown) | [![Build Status](https://travis-ci.org/workshopper/how-to-markdown.svg?branch=master)](https://travis-ci.org/workshopper/how-to-markdown)
how-to-npm | [![npm](https://img.shields.io/npm/v/how-to-npm.svg)](https://www.npmjs.com/package/how-to-npm) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/how-to-npm.svg)](https://github.com/workshopper/how-to-npm) | [![Build Status](https://travis-ci.org/workshopper/how-to-npm.svg?branch=master)](https://travis-ci.org/workshopper/how-to-npm)
i18n-it-all | [![npm](https://img.shields.io/npm/v/i18n-it-all.svg)](https://www.npmjs.com/package/i18n-it-all) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/i18n-it-all.svg)](https://github.com/workshopper/i18n-it-all) | [![Build Status](https://travis-ci.org/workshopper/i18n-it-all.svg?branch=master)](https://travis-ci.org/workshopper/i18n-it-all)
javascripting | [![npm](https://img.shields.io/npm/v/javascripting.svg)](https://www.npmjs.com/package/javascripting) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/javascripting.svg)](https://github.com/workshopper/javascripting) | [![Build Status](https://travis-ci.org/workshopper/javascripting.svg?branch=master)](https://travis-ci.org/workshopper/javascripting)
learn-sass | [![npm](https://img.shields.io/npm/v/learn-sass.svg)](https://www.npmjs.com/package/learn-sass) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/learn-sass.svg)](https://github.com/workshopper/learn-sass) | [![Build Status](https://travis-ci.org/workshopper/learn-sass.svg?branch=master)](https://travis-ci.org/workshopper/learn-sass)
learnyounode | [![npm](https://img.shields.io/npm/v/learnyounode.svg)](https://www.npmjs.com/package/learnyounode) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/learnyounode.svg)](https://github.com/workshopper/learnyounode) | [![Build Status](https://travis-ci.org/workshopper/learnyounode.svg?branch=master)](https://travis-ci.org/workshopper/learnyounode)
learnyoureact | [![npm](https://img.shields.io/npm/v/learnyoureact.svg)](https://www.npmjs.com/package/learnyoureact) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/learnyoureact.svg)](https://github.com/workshopper/learnyoureact) | [![Build Status](https://travis-ci.org/workshopper/learnyoureact.svg?branch=master)](https://travis-ci.org/workshopper/learnyoureact)
levelmeup | [![npm](https://img.shields.io/npm/v/levelmeup.svg)](https://www.npmjs.com/package/levelmeup) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/levelmeup.svg)](https://github.com/workshopper/levelmeup) | [![Build Status](https://travis-ci.org/workshopper/levelmeup.svg?branch=master)](https://travis-ci.org/workshopper/levelmeup)
regex-adventure | [![npm](https://img.shields.io/npm/v/regex-adventure.svg)](https://www.npmjs.com/package/regex-adventure) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/regex-adventure.svg)](https://github.com/workshopper/regex-adventure) | [![Build Status](https://travis-ci.org/workshopper/regex-adventure.svg?branch=master)](https://travis-ci.org/workshopper/regex-adventure)
scope-chains-closures | [![npm](https://img.shields.io/npm/v/scope-chains-closures.svg)](https://www.npmjs.com/package/scope-chains-closures) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/scope-chains-closures.svg)](https://github.com/workshopper/scope-chains-closures) | [![Build Status](https://travis-ci.org/workshopper/scope-chains-closures.svg?branch=master)](https://travis-ci.org/workshopper/scope-chains-closures)
stream-adventure | [![npm](https://img.shields.io/npm/v/stream-adventure.svg)](https://www.npmjs.com/package/stream-adventure) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/stream-adventure.svg)](https://github.com/workshopper/stream-adventure) | [![Build Status](https://travis-ci.org/workshopper/stream-adventure.svg?branch=master)](https://travis-ci.org/workshopper/stream-adventure)
workshopper | [![npm](https://img.shields.io/npm/v/workshopper.svg)](https://www.npmjs.com/package/workshopper) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/workshopper.svg)](https://github.com/workshopper/workshopper) | [![Build Status](https://travis-ci.org/workshopper/workshopper.svg?branch=master)](https://travis-ci.org/workshopper/workshopper)
workshopper-adventure | [![npm](https://img.shields.io/npm/v/workshopper-adventure.svg)](https://www.npmjs.com/package/workshopper-adventure) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/workshopper-adventure.svg)](https://github.com/workshopper/workshopper-adventure) | [![Build Status](https://travis-ci.org/workshopper/workshopper-adventure.svg?branch=master)](https://travis-ci.org/workshopper/workshopper-adventure)
workshopper-adventure-storage | [![npm](https://img.shields.io/npm/v/workshopper-adventure-storage.svg)](https://www.npmjs.com/package/workshopper-adventure-storage) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/workshopper-adventure-storage.svg)](https://github.com/workshopper/workshopper-adventure-storage) | [![Build Status](https://travis-ci.org/workshopper/workshopper-adventure-storage.svg?branch=master)](https://travis-ci.org/workshopper/workshopper-adventure-storage)
workshopper-adventure-test | [![npm](https://img.shields.io/npm/v/workshopper-adventure-test.svg)](https://www.npmjs.com/package/workshopper-adventure-test) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/workshopper-adventure-test.svg)](https://github.com/workshopper/workshopper-adventure-test) | [![Build Status](https://travis-ci.org/workshopper/workshopper-adventure-test.svg?branch=master)](https://travis-ci.org/workshopper/workshopper-adventure-test)
workshopper-boilerplate | [![npm](https://img.shields.io/npm/v/workshopper-boilerplate.svg)](https://www.npmjs.com/package/workshopper-boilerplate) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/workshopper-boilerplate.svg)](https://github.com/workshopper/workshopper-boilerplate) | [![Build Status](https://travis-ci.org/workshopper/workshopper-boilerplate.svg?branch=master)](https://travis-ci.org/workshopper/workshopper-boilerplate)
workshopper-exercise | [![npm](https://img.shields.io/npm/v/workshopper-exercise.svg)](https://www.npmjs.com/package/workshopper-exercise) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/workshopper-exercise.svg)](https://github.com/workshopper/workshopper-exercise) | [![Build Status](https://travis-ci.org/workshopper/workshopper-exercise.svg?branch=master)](https://travis-ci.org/workshopper/workshopper-exercise)
workshopper-more | [![npm](https://img.shields.io/npm/v/workshopper-more.svg)](https://www.npmjs.com/package/workshopper-more) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/workshopper-more.svg)](https://github.com/workshopper/workshopper-more) | [![Build Status](https://travis-ci.org/workshopper/workshopper-more.svg?branch=master)](https://travis-ci.org/workshopper/workshopper-more)
workshopper-wrappedexec | [![npm](https://img.shields.io/npm/v/workshopper-wrappedexec.svg)](https://www.npmjs.com/package/workshopper-wrappedexec) | [![GitHub tag](https://img.shields.io/github/tag/workshopper/workshopper-wrappedexec.svg)](https://github.com/workshopper/workshopper-wrappedexec) | [![Build Status](https://travis-ci.org/workshopper/workshopper-wrappedexec.svg?branch=master)](https://travis-ci.org/workshopper/workshopper-wrappedexec)

## Requirements

Please prepare the following prerequisites for package deployment:

- New version of the package should follow [semantic versioning](http://semver.org/).
- Ensure that the project github repository of the workshopper is correctly setup and working with [Travis CI](http://travis-ci.org/).
- Master branch of the github repository has at least basic coverage for tests and code quality.
- Provide comprehensive changelog for the release.

Please note that deployments to npm are made regularly and on request. Hotfixes with urgency are discouraged (i.e. please respect the time of volunteers working on the deployments)

## Submiting a deployment request

Steps to follow:
- Please read and prepare the prerequisites mentioned in the "Requirements" section.
- Create a request ticket on the board for [deployment requests](https://github.com/workshopper/org/projects/1).
- Be patient and provide support where and when necessary.

## Guidelines

This list is aimed to help you progress in preparing your package for deployment.

### Travis CI
- Free service for open source projects.
- Runs tests and code quality checks automatically.
- The master branch of your repository should be passing the checks.

Here's an example shield you can [take for your particular repository](https://docs.travis-ci.com/user/status-images/).
```md
[![Build Status](https://travis-ci.org/workshopper/javascripting.svg?branch=master)](https://travis-ci.org/workshopper/javascripting)
```
[Further reading on Travis CI with node.js](https://docs.travis-ci.com/user/languages/javascript-with-nodejs/).

### Changelogs
- Should be named as CHANGELOG or CHANGELOG.md
- Should reside in the root of the master of the github repository
- Should contain brief information about the changes done between releases
- Could use an automated tool such as [standard-version](https://github.com/conventional-changelog/standard-version)

Here's an example of [automatically generated changelog](https://github.com/angular/angular.js/blob/master/CHANGELOG.md) 
which can be generated following [commit message conventions](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#commit).
