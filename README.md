# iohk-monitoring-framework

[![Build status](https://badge.buildkite.com/1cc7939a1fed4972c15b8f87d510e0404b0eb65d73cfd1e30b.svg?branch=develop)](https://buildkite.com/input-output-hk/iohk-monitoring-framework)

This framework provides logging, benchmarking and monitoring.

## overview

![Overview of modules](docs/OverviewModules.png)

## documentation

Documentation of the [source code](docs/IOHK-Monitoring-code.pdf) and
[tests](docs/IOHK-Monitoring-tests.pdf) are available in PDF format.

## building

`cabal new-build`

`cabal new-test`

## development

`ghcid -c "cabal new-repl"` watches for file changes and recompiles them immediately
