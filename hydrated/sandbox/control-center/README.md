# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout 3458b6e274c6dc465d6248a7be6edb62544bea98
helm template . --name-template sandbox-control-center --values ./charts/incubator/hyperswitch-control-center/helm-sandox-values.yaml --include-crds
```
