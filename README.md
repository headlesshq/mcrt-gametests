<h1 align="center" style="font-weight: normal;"><b>MC-Runtime-Test-GameTests</b></h1>
<p align="center">An example of how to run gametests in <a href="https://github.com/headlesshq/mc-runtime-test">Mc-Runtime-Test</a>.</p>
<p align="center">MC-Runtime-Test | <a href="https://github.com/3arthqu4ke/headlessmc">HMC</a> | <a href="https://github.com/3arthqu4ke/hmc-specifics">HMC-Specifics</a> | <a href="https://github.com/3arthqu4ke/hmc-optimizations">HMC-Optimizations</a></p>

<div align="center">

[![GitHub All Releases](https://img.shields.io/github/downloads/headlesshq/mc-runtime-test-mod/total.svg)](https://github.com/headlesshq/mc-runtime-test-mod/releases)
![](https://github.com/headlesshq/mc-runtime-test-mod/actions/workflows/run-matrix.yml/badge.svg)
![GitHub](https://img.shields.io/github/license/headlesshq/mc-runtime-test-mod)
![Github last-commit](https://img.shields.io/github/last-commit/headlesshq/mc-runtime-test-mod)

</div>

This a mod that showcases how you can run 
[gametests](https://learn.microsoft.com/en-us/minecraft/creator/documents/gametestgettingstarted) 
on the Minecraft Java Edition client with the [mc-runtime-test](https://github.com/headlesshq/mc-runtime-test) 
Github action.
The action allows you to run the Minecraft Java client inside your Github CI/CD pipeline for testing purposes.

This is just a demo, gametest support is not fully stable yet in mc-runtime-test.

We have set up gametests [here](src/main/java/me/earth/clientgametest/GameTests.java).
Some mixin magic was required to get this running on all mod loaders.
The workflow is [here](.github/workflows/run-gametests.yml).
