# Compatibiliy Guidelines for Workshoppers

To make it easier to decide for the various workshoppers what versions they should be compatible with and to give
users and mentors a way to clearly communicate the compatibility of workshoppers.

## Node.js

Users of workshoppers like to learn about Node. It is reasonable that workshoppers take advantage and point
out the features of newer versions of node to educate.

**Workshoppers should only be expected to support the Node.js LTS and Stable releases that are not older than a year.**

i.e. On Feb. 17, 2017 this would include following versions:
```
>=7.0.0 <=7.5.0
>=6.0.0 <=6.9.5
>=5.7.0 <=5.12.0
>=4.3.2 <=4.7.3
```

## Operating Systems & CLI's

Workshoppers should run on user-facing operation systems that might reasonably be used at study events:

**Windows, Mac OS, debian-based(Ubuntu, LinuxMint) and Raspberry PI**.

There are however restrictions on command lines to support: Particularily the cygwin bash on windows is problematic.

See https://github.com/nodejs/node/issues/3006

## Framework compatibility

The workshoppers should be tested upon release with the latest version of [workshopper-adventure-test](https://github.com/workshopper/workshopper-adventure-test).
