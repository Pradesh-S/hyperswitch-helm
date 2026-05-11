# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout 39384384e8b036aa8da5fed727fb3a5ab61e38db
helm template . --name-template test-control-center-hydrator-prod-version --namespace hyperswitch-prod --values ./infra-configurations/prod-values.yaml --include-crds
```
