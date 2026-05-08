# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout 7a42105b31f4c23a81f3f16d467adae943cea22c
helm template . --name-template test-control-center-hydrator-version-10z --values ./charts/incubator/hyperswitch-control-center/infra-configurations/sandbox-values.yaml --values ./charts/incubator/hyperswitch-control-center/deployment-configs/sandbox-values.yaml --include-crds
```
