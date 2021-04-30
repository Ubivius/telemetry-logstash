# Telemetry-Logstash

A tool that aggregates and structures logs of the cluster's components

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

- logstash · elastic/logstash (https://artifacthub.io/packages/helm/elastic/logstash)

Once Helm is set up properly, add the repo as follows:

## Get Repo Info

```console
$ helm repo add elastic https://helm.elastic.co
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `logstash`:

```console
$ helm install logstash --version <version> elastic/logstash -f chart/values.yaml
```

## Uninstalling the Chart

To uninstall/delete the logstash deployment:

```console
$ helm delete logstash
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
