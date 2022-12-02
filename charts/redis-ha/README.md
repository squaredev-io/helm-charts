# Redis HA Helm Chart

This Helm chart provides a Redis High Availability Configuration (HA) with primary/secondary failover configuration.

## Get Repo Info

```console
helm repo add squaredev-io https://squaredev-io.github.io/helm-charts
helm repo update
```

_See [helm repo](https://helm.sh/docs/helm/helm_repo/) for command documentation._

## Prerequisites

- Helm 3+
- Kubernetes 1.8+ with Beta APIs enabled
- PV provisioner support in the underlying infrastructure

## Installing the Chart

To install the chart with the release name `my-release`:

```console
helm install my-release squaredev-io/redis-ha
```

## Uninstalling the Chart

To uninstall/delete the my-release deployment:

```console
helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration

> Coming Soon
