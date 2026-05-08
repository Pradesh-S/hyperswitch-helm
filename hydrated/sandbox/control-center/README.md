# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout fe82825cbcdf64f3daf3398ecaa7775f8df057b1
helm template . --name-template test-control-center-hydrator-sandbox-version --values ./infra-configurations/sandbox-values.yaml --values ./deployment-configs/sandbox-values.yaml --include-crds
```
