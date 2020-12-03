# Pyroscope

[![Tests Status](https://github.com/pyroscope-io/pyroscope/workflows/Tests/badge.svg)](https://github.com/pyroscope-io/pyroscope/actions)
[![Release Status](https://github.com/pyroscope-io/pyroscope/workflows/Release/badge.svg)](https://github.com/pyroscope-io/pyroscope/actions)


# What is Pyroscope?

Pyroscope is an open source continuous profiling platform. It profiles your backend applications 24/7 allowing you to see where your programs spend time.

Pyroscope is designed around a few key requirements:
* low CPU overhead for the profiling targets
* low disk space requirements
* snappy UI


## Demo

TODO


## Architecture

![Architecture Diagram](.github/markdown-images/architecture.svg)]

Currently the agent communicates with the target application via a UNIX socket. Agent Co

## Currently Available Integrations

* [x] ruby / rails
* [x] python (partially working)
* [ ] linux eBPF (coming soon)
* [ ] golang (coming soon)


## Downloads

You can download the latest version of pyroscope from our GitHub [Releases page](https://github.com/pyroscope-io/pyroscope/releases/latest).

[//]: contributor-faces