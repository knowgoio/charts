# KnowGo Helm Charts Repository

This repository provides [Helm](https://helm.sh) Charts for use with the KnowGo Platform.

## Repository Overview

The repository is split out into the following structure:

| Repository | Description                                                                         |
| -----------|-------------------------------------------------------------------------------------|
| dev        | In-development / incubating Helm charts for core `KnowGo` platform components       |
| stable     | Production-ready Helm charts for deploying core `KnowGo` platform components        |
| community  | Third-party and community developed Helm charts for use with the `KnowGo` platform  |


## Adding Repositories

Each repository should be added individually:

```shell script
$ helm repo add --username <github-username> --password <github-password> \
    knowgo-helm-<repository> https://raw.githubusercontent.com/knowgoio/knowgo-helm-charts/master/repo/<repository>
```
