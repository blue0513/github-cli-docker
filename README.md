# GitHub CLI Docker

This is a Docker image for GitHub CLI.

*To install GitHub CLI, please follow [the official instructions](https://github.com/cli/cli/blob/trunk/docs/install_linux.md)

## Usage

```console
$ docker build . -t github-cli-docker
$ docker run --rm -it github-cli-docker gh --version
```
