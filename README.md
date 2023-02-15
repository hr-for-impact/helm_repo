# Modify and publish chart

## Create helm chart package

```sh
$ helm package <chart_folder_name>
```
ex: `helm package cms`

## Index packaged chart in repo

```sh
# refresh index.yaml
$ helm repo index .  --url=https://hr-for-impact.github.io/helm_repo
```