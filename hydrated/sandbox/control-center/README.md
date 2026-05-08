# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout 0b37a710a83a2a99bca9ea721c781363736c9fec
helm template . --name-template test-control-center-hydrator-version-10f-version --values ./charts/incubator/hyperswitch-control-center/infra-configurations/sandbox-values.yaml --values ./charts/incubator/hyperswitch-control-center/deployment-configs/sandbox-values.yaml --include-crds
```
