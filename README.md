# Corepack installs Yarn 1.x Integration Test

This repository provides an extremely simple Yarn 1.x project which can
be used to test whether corepack installs the version of yarn specified by
[packageManager](https://nodejs.org/docs/latest-v20.x/api/packages.html#packagemanager) in package.json.

In the current implementation of Yarn 1.x support in Cachi2, this field should be ignored. A version of Yarn 3.x
is specified as the value of packageManager here even though the project uses Yarn 1.x in order to aid detection of
an incorrect outcome in the test.
