# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout 429759d54ab7b641d661ec10cccb33e4032f6264
helm template . --name-template test-control-center-hydrator --values ./infra-configurations/sandbox-values.yaml --values ./deployment-configs/sandbox-values.yaml --include-crds
```
