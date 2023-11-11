[![Automatic version updates](https://github.com/ZOSOpenTools/zoslibport/actions/workflows/bump.yml/badge.svg)](https://github.com/ZOSOpenTools/zoslibport/actions/workflows/bump.yml)

## ZOSLIB

ZOSLIB is a z/OS C/C++ library, available in https://github.com/ibmruntimes/zoslib. It is an extended implementation of the z/OS LE C Runtime Library.

## How do I make use of zoslib?

Just add zoslib as a dependency and zoslib and it will automatically be statically linked to your application.

For example:
```bash
ZOPEN_TARBALL_DEPS="make gzip tar zoslib"
```
