sonic-logging
=============

This repo contains logging utilities for the SONiC project which provide a simple wrapper for syslog activities. These activies allow the addition of line number, as well as other additional activities.

You can optionally use the CLI for runtime modification of logging levels called `sonic_logging_cli`.

All headers are located in sonic and will be installed in the */usr/include/sonic* folder (based on your prefix).

Build
--------
See [sonic-nas-manifest](https://github.com/Azure/sonic-nas-manifest) for complete information on common build tools.

### Build dependencies
None

BUILD CMD: `sonic_build  -- clean binary`

(c) Dell 2016
