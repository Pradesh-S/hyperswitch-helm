# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout 01ad69bf65d23fd6e55f64c6046599e46a4f5d26
helm template . --name-template test-control-center-hydrator-version-10p --values ./infra-configurations/prod-values.yaml --values ./deployment-configs/prod-values.yaml --include-crds
```
