# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout b62ab9b167a81a09471baa21727a7b3d08412613
helm template . --name-template test-control-center-hydrator --values ./charts/incubator/hyperswitch-control-center/infra-configurations/sandbox-values.yaml --values ./charts/incubator/hyperswitch-control-center/deployment-configs/sandbox-values.yaml --include-crds
```
