# Kerberos Dev Container

This projects contains a devbox or devcontainer, what you would like to name it, that includes all the tools and libraries to work in the Kerberos Ecosystem.

## What can you expect?

In this dev container you find following dependencies.

- FFmpeg: n4.4.1 Copyright (c) 2000-2021 the FFmpeg developers
  built with gcc 10 (Debian 10.2.1-6)
- Golang: go1.18 linux/amd64
- NPM: 8.15.0
- Node: 16.17.0
- OpenCV: 4.5.5

## How to build this project

It's easy just build the container, or make a change (PR) and GitHub actions will create a new release.

    docker build -t kerberos/devcontainer .