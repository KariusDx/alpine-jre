# alpine-jre

[![Build Status](https://travis-ci.org/travis-ci/travis-build.svg?branch=master)](https://travis-ci.org/KariusDx/alpine-jre)

Docker image with Java Runtime Environment on Alpine Linux.

Includes modern `bash`.

## Details

* Alpine 3.8 (2018-07-17)
* bash 4.4.19 (2018-02-06)
* OpenJDK jre 8u181 (2018-07-17)

## Usage

    docker pull kariusdx/alpine-jre:3.8-8u181

## Recipes

The following recipes are defined in [justfile](justfile):

| Recipe            | Description                                                                                      |
|:------------------|:-------------------------------------------------------------------------------------------------|
| `build`           | Builds the `kariusdx/alpine-jre` docker image.                                                   |
| `help`            | Lists all available recipes, their calling syntax, and synopsis.                                 |
| `publish +TAGS`   | Publishes `kariusdx/alpine-jre` to docker hub with the given `TAGS`.                             |
| `run +ARGS`       | Runs a command in `kariusdx/alpine-jre`.                                                         |
| `shell`           | Runs a shell in `kariusdx/alpine-jre` for poking around.                                         |
| `tags`            | List the tags that point at `HEAD`.                                                              |

Newly added recipes should be documented above.
