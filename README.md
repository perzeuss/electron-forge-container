# Electron Forge Docker Container

![Docker Build](https://github.com/perzeuss/electron-forge-container/workflows/Docker%20Image%20CI/badge.svg)
[![Docker Hub](https://img.shields.io/docker/automated/perzeuss/electron-forge-ci.svg)](https://hub.docker.com/r/perzeuss/electron-forge-ci/)

Used to run CI for [Electron Forge](https://github.com/electron-userland/electron-forge) on Linux,
but can also be used as a base to build Electron app packages for Linux via Electron Forge.

## Usage

```docker
FROM malept/electron-forge-container:latest

# …other Docker commands…
```
