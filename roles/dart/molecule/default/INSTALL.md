# Podman driver installation guide

## Requirements

- Podman

## Install

Please refer to the [pypa/pipenv](https://github.com/pypa/pipenv) documentation for installation best practices.

If the `Pipefile` exists, you can install packages with the following command:

```shell
$ pipenv install
```

Otherwise:

```shell
$ pipenv install molecule[podman] selinux
```
