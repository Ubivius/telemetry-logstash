# Telemetry-Logstash

A tool that aggregates and structures logs of the cluster's components

# Logstash Helm Chart

- logstash · elastic/logstash (https://artifacthub.io/packages/helm/elastic/logstash)

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
