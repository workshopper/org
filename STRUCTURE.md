# Structure

## Ownership

All projects of the workshopper organization are [OSS](https://en.wikipedia.org/wiki/Open-source_software) projects.
Licensed either under the [ISC License](https://tldrlegal.com/license/-isc-license) _(preferred)_ or the compatible
[MIT license](https://tldrlegal.com/license/mit-license). As such the direction of every project is 
of the authors/contributors. There is no legal body and no [BDFL](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life)
that exercises control over the projects.

## Purpose

This organization exists to unite the effort of the creation of OSS learning material, workshoppers.
It should help in answering questions such as _"How do I specify dependencies?"_, _"Where can I find translators?"_,
_"How should I test my work?"_, _"How can I retire as maintainer?"_. _"What way are others interested to go?"_. etc.

## Goal

**Better OSS learning materials.**

_This organization is built around the Node.js platform and has its roots with the NodeSchool. As a result a lot of the
material is related to Node.js and as of March 2017 all of the code is published on NPM. This doesn't mean though that
the door is necessarily closed for material in or for other languages._

## Membership

Membership is not required for contribution or attribution. Each project/repository maintains a list of contributors
and **anyone** is free to improve or build on the work here. For managing issues or if you want to transfer 
some work to this organization it might be better if you become a member. In that case please [create an issue](https://github.com/workshopper/org/issues/new)
mentioning which repo you need access for. One of the leads of the project/repository has to confirm your appointment.

## Hierarchy

### Core Team

The core team exists to limit complete access to the organization. The core team has full write permission to the organization.
This destinction exists **for safety reasons only**.

### Lead maintainers

Lead maintainers are individuals that stepped up and declared themselves as maintainers/person-answering-questions for a
project. Except for the [Deploy Team](#deploy-team), the lead maintainers are the only group that definitely has admin access
to the repository in question and the related npm project.

| Repository | Lead |
|------------|------|
| [adventure](https://github.com/workshopper/adventure) ※¹ | _[@substack](https://github.com/substack)_ ※² |
| [browserify-adventure](https://github.com/workshopper/browserify-adventure) | _[@substack](https://github.com/substack)_ ※² |
| [goingnative](https://github.com/workshopper/goingnative) | _[@rvagg](https://github.com/rvagg)_ ※² |
| [how-to-markdown](https://github.com/workshopper/how-to-markdown) | [@denysdovhan](https://github.com/denysdovhan) |
| [how-to-npm](https://github.com/workshopper/how-to-npm) | [@watilde](https://github.com/watilde), [@EmmaRamirez](https://github.com/EmmaRamirez), [@pnn](https://github.com/pnn) |
| [i18n-it-all](https://github.com/workshopper/i18n-it-all) | [@martinheidegger](https://github.com/martinheidegger) |
| [javascripting](https://github.com/workshopper/javascripting) | [@sethvincent](https://github.com/sethvincent), [@SomeoneWeird](https://github.com/SomeoneWeird), [@AnshulMalik](https://github.com/AnshulMalik), [@itzsaga](https://github.com/itzsaga), [@AVGP](https://github.com/AVGP), [@sauban](https://github.com/sauban) |
| [learn-sass](https://github.com/workshopper/learn-sass) | [@claudiopro](https://github.com/claudiopro) |
| [learnyounode](https://github.com/workshopper/learnyounode) | [@martinheidegger](https://github.com/martinheidegger) |
| [learnyoureact](https://github.com/workshopper/learnyoureact) | [@kohei-takata](https://github.com/kohei-takata) |
| [levelmeup](https://github.com/workshopper/levelmeup) | [@martinheidegger](https://github.com/martinheidegger) |
| [list](https://github.com/workshopper/list) | _[@linclark](https://github.com/linclark)_ ※² |
| [org](https://github.com/workshopper/org) | [@martinheidegger](https://github.com/martinheidegger) |
| [regex-adventure](https://github.com/workshopper/regex-adventure) | _[@substack](https://github.com/substack)_ ※² |
| [scope-chains-closures](https://github.com/workshopper/scope-chains-closures) | [@jesstelford](https://github.com/jesstelford), [@SomeoneWeird](https://github.com/SomeoneWeird) |
| [stream-adventure](https://github.com/workshopper/stream-adventure) | [@kalinchernev](https://github.com/kalinchernev) |
| [workshopper](https://github.com/workshopper/workshopper) ※¹ | [@martinheidegger](https://github.com/martinheidegger) |
| [workshopper-adventure](https://github.com/workshopper/workshopper-adventure) | [@martinheidegger](https://github.com/martinheidegger) |
| [workshopper-adventure-storage](https://github.com/workshopper/workshopper-adventure-storage) | [@kid-icarus](https://github.com/kid-icarus) |
| [workshopper-adventure-test](https://github.com/workshopper/workshopper-adventure-test) | [@martinheidegger](https://github.com/martinheidegger) |
| [workshopper-boilerplate](https://github.com/workshopper/workshopper-boilerplate) | _[@rvagg](https://github.com/rvagg)_ ※² |
| [workshopper-exercise](https://github.com/workshopper/workshopper-exercise) | [@martinheidegger](https://github.com/martinheidegger) |
| [workshopper-more](https://github.com/workshopper/workshopper-more) ※¹ | _[@rvagg](https://github.com/rvagg)_ ※² |
| [workshopper-wrappedexec](https://github.com/workshopper/workshopper-wrappedexec) | _[@rvagg](https://github.com/rvagg)_ ※² |

_※¹ = Legacy project or likely to be deprecated in future._<br>
_※² = Original maintainer. No active, current maintainer. Open for people to step up._

Generally there is always a vacancy for maintainers unless specifically mentioned by the maintainer. Post an issue in the org
repository if you want to become an maintainer.

### Deploy Team

The Deploy team _([link](https://github.com/orgs/workshopper/teams/deploy) only works if you are an org member)_ are members
that have access to write access to all repos and the permission to deploy every repo to NPM.
