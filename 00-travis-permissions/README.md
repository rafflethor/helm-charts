# Travis permissions

[Travis-CI](http://www.travis-ci.org) is a free and open source, continuous integration platform.

## TL;DR;

```bash
$ helm install ./00-travis-permissions
```

## Introduction

This chart installs a role to be able to operate `kubectl` command from Travis-CI using the [Helm](https://helm.sh) package manager.

## Installing the Chart

To install the chart with the release name `my-release`:

```bash
$ helm install --name my-release ./00-travis-permissions
```

The command deploys Redmine on the Kubernetes cluster in the default configuration. The [configuration](#configuration) section lists the parameters that can be configured during installation.

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```bash
$ helm delete my-release
```

## Configuration

No configuration parameters are available
