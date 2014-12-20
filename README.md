# A debian package for Registrator

## Overview

This project can be used to create a debian package for any tag in the
[Registrator](https://github.com/progrium/registrator) git repository
A simple

    $ make

will package the latest tag, but any other version tag can be specified using
the `VERSION` variable, e.g.

    $ make VERSION=0.4.0