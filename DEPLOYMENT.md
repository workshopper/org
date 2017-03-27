# Deployment of workshoppers

Below you can find details regarding the deployment process of [workshoppers on npm](https://www.npmjs.com/org/workshopper). 
This information is mainly aimed to be used by [workshopper teams](https://github.com/orgs/workshopper/teams).

## Workshoppers versioning

In the table below you will find an overview of package versioning
between latest release in github and npm.

workshopper | NPM version   | Master of workshopper | Build | NodeJs LTS compatible |
------------| ----------- | --------------------- | ----- | ---- |
learnyounode | 3.5.10 | [3.5.10](https://github.com/workshopper/learnyounode) | [![Build Status](https://travis-ci.org/workshopper/learnyounode.svg?branch=master)](https://travis-ci.org/workshopper/learnyounode) | ✗
javascripting | 2.6.1 | [2.6.1](https://github.com/workshopper/javascripting) | [![Build Status](https://travis-ci.org/workshopper/javascripting.svg?branch=master)](https://travis-ci.org/workshopper/javascripting) | ✗

## Requirements

Please prepare the following prerequisites for package deployment:

- New version of the package should follow [semantic versioning](http://semver.org/);
- Ensure project github repository of the workshopper is correctly setup and working with [Travis CI](http://travis-ci.org/);
- Master branch of the github repository has at least basic coverage for tests and code quality;
- Provide comprehensive changelog for the release;

Please note that deployments to npm are made regularly and on request. Hotfixes with urgency are discouraged (i.e. please respect the time of volunteers working on the deployments)

## Submiting a deployment request

Steps to follow:
- Please read and prepare the prerequisites mentioned in the "Requirements" section
- Create a request ticket on the board for [deployment requests](https://github.com/workshopper/org/projects/1)
- Be patient and provide support where necessary

## Guidelines

This list is aimed to help you progress in preparing your package for deployment.

### Travis CI
- Free service for open source projects;
- Runs tests and code quality checks automatically;
- The master branch of your repository should be passing the checks;

Here's an example badge you can [take for your particular repository](https://docs.travis-ci.com/user/status-images/).
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
