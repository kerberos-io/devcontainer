# Kerberos Dev Container

This projects contains a devbox or devcontainer, what you would like to name it, that includes all the tools and libraries to work in the Kerberos Ecosystem.

## What can you expect?

In this dev container you find following dependencies.

- FFmpeg: n5.0.1
- Golang: go1.19
- NPM: 8.15.0
- Node: 16.17.0
- Python 3.9.2

## How to build this project

It's easy just build the container, or make a change (PR) and GitHub actions will create a new release.

    docker build -t kerberos/devcontainer .
