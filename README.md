# Dockerized Github Changelog Generator

[![Release build](https://github.com/DIAGNijmegen/rse-docker-github-changelog-generator/actions/workflows/docker-image.yml/badge.svg)](https://github.com/DIAGNijmegen/rse-docker-github-changelog-generator/actions/workflows/docker-image.yml)

This is an official containerization of [Github Changelog Generator](https://github.com/github-changelog-generator/github-changelog-generator).

For each Github Changelog Generator release, you will find the corresponding docker image tag.

## How to Run this Image

```shell
docker run -it --rm -v "$(pwd)":/usr/local/src/your-app githubchangeloggenerator/github-changelog-generator
```
