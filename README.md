# gotify Helm Chart
![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/gotify)](https://artifacthub.io/packages/search?repo=gotify)

From https://gotify.net/:
> Gotify a simple server for sending and receiving messages ## That's all!

## Get Repo Info

    helm repo add my-gotify https://pmoscode-helm.github.io/gotify/
    helm repo update

## Install chart

    helm install [RELEASE_NAME] my-gotify/gotify

The command deploys gotify on the Kubernetes cluster in the default configuration.

See configuration below.

See [helm install](https://helm.sh/docs/helm/helm_install/) for command documentation.

## Uninstall Chart

    helm uninstall [RELEASE_NAME]

This removes all the Kubernetes components associated with the chart and deletes the release.

See [helm uninstall](https://helm.sh/docs/helm/helm_uninstall/) for command documentation.

## Upgrading Chart

    helm upgrade [RELEASE_NAME] [CHART] --install

See [helm upgrade](https://helm.sh/docs/helm/helm_upgrade/) for command documentation.

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| image.pullPolicy | string | `"Always"` | pull policy |
| image.repository | string | `"gotify/server"` | repository with gotify image |
| image.tag | string | `"2.2.4"` | current version of the image |
| imagePullSecrets | list | `[]` | imagePullSecrets (not needed, if default image is used) |
| ingress | object | `{"annotations":{},"className":"","enabled":false,"hosts":[{"host":"chart-example.local","paths":[{"path":"/","pathType":"ImplementationSpecific"}]}],"tls":[]}` | Configure ingress |
| persistence.accessMode | string | `"ReadWriteOnce"` | accessMode |
| persistence.enabled | bool | `false` | enable persistence when true |
| persistence.size | string | `"20Gi"` | default storage size |
| persistence.storageClass | string | `""` | actual storageClass |
| server.databaseConnection | string | `""` | set connection string for mysql (gotify:secret@/gotifydb?charset=utf8&parseTime=True&loc=Local) or postgresql (host=localhost port=3306 user=gotify dbname=gotify password=secret) |
| server.databaseDialect | string | `"sqlite3"` | select database kind (sqlite3, mysql, postgres) |
| server.defaultUserName | string | `"admin"` | default user |
| server.defaultUserPassword | string | `"admin"` | default user password |
| server.passstrength | int | `10` | minimal password length |
| server.registration | bool | `false` | is user registration enabled? |
| server.timezone | string | `"Europe/Berlin"` | server timezone |
| service.port | int | `80` |  |
| service.type | string | `"ClusterIP"` |  |
| serviceAccount.annotations | object | `{}` | add annotations to serviceAccount |
| serviceAccount.create | bool | `true` | enable serviceAccount |
| serviceAccount.name | string | `""` | name of the serviceAccount (will be generated if empty) |

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| pmoscode | <info@pmoscode.de> | <https://pmoscode.de> |
