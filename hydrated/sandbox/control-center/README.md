# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout b04b4e720e4ba7e2f6adabf8d3930b992a714ae1
helm template . --name-template test-control-center-hydrator-simple --values ./charts/incubator/hyperswitch-control-center/infra-configurations/sandbox-values.yaml --values ./charts/incubator/hyperswitch-control-center/deployment-configs/sandbox-values.yaml --include-crds
```
