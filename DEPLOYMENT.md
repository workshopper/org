# [DRAFT] Deployment of workshoppers

Suggesting steps to organize the process of publishing changes from workshoppers to npm.

## Workshoppers versions

Below, you can find a dashboard monitoring differences in versions of workshopper packages between github and npm.

workshopper | NPM version   | Master of workshopper | Build | NodeJs LTS compatible |
------------| ----------- | --------------------- | ----- | ---- |
learnyounode | 3.5.10 | [3.5.10](https://github.com/workshopper/learnyounode) | [![Build Status](https://travis-ci.org/workshopper/learnyounode.svg?branch=master)](https://travis-ci.org/workshopper/learnyounode) | ✗
javascripting | 2.6.1 | [2.6.1](https://github.com/workshopper/javascripting) | [![Build Status](https://travis-ci.org/workshopper/javascripting.svg?branch=master)](https://travis-ci.org/workshopper/javascripting) | ✗

## Requirements

Please be kind to prepare the following prerequisites before asking or publishing your package to npm:

- New version of the package should follow semantic versioning
- Ensure that the github repository of the workshopper is correctly setup and working with [Travis CI](http://travis-ci.org/).
- Master branch of workshopper github repository is "buildable", i.e. not broken (Tests are passing, and the lint and other code standards changes are acceptable)
- Comprehensible change log is provided on the workshopper github master branch in a CHANGELOG.md file. This could be made manually while making a new release on the repository, or prepared automatically from a script (read further below for suggestions)

Please note that deployments to npm are made regularly and on request. Hotfixes with urgency are discouraged (i.e. please respect the time of volunteers working on the deployments)

## Submit deployment request

Assuming you want to have a deployment of your package to npm:
- Please read and prepare the prerequisites mentioned in the "Requirements" section
- Create a request ticket on the board for [deployment requests](https://github.com/workshopper/org/projects)
- Be patient and provide support where necessary

## Guidelines

This list is aimed to help you in making quick progress in meeting the requirements for deploying your workshopper on npm.

### Travis CI
- Free service for open source projects
- The repository should shall a green badge when you embed the following markup in your README.md in the root folder of the workshopper github repository

```md
[![Build Status](https://travis-ci.org/workshopper/javascripting.svg?branch=master)](https://travis-ci.org/workshopper/javascripting)
```
- [Read further](https://docs.travis-ci.com/user/languages/javascript-with-nodejs/) about node.js specific environments.

### Change logs
- Should be named as CHANGELOG or CHANGELOG.md
- Should reside in the root of the master of the github repository
- Should contain brief information about the changes done between releases
- Could use an automated tool such as [standard-version](https://github.com/conventional-changelog/standard-version) or
