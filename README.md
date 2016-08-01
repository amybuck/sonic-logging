SONiC Logging
=============

Logging APIs for the SONiC project.

Description
-----------

This repo contains logging utilities for SONiC project.  The logging utilities provide a simple wrapper for syslog allowing the addition of things like line number and other details.

There is a CLI that will allow runtime modification of logging levels as well called sonic_logging_cli.

All headers are located in sonic and will be installed in the /usr/include/sonic folder (based on your prefix).

Building
--------
Please see the instructions in the sonic-nas-manifest repo for more details on the common build tools.  [Sonic-nas-manifest](https://github.com/Azure/sonic-nas-manifest)

Build Dependencies:
  - None

BUILD CMD: sonic_build  -- clean binary

(c) Dell 2016

