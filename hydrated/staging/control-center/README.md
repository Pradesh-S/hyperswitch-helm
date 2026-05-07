# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout 4870867a3cb07f01f183c14000d424f1ebee4ebc
helm template . --name-template control-center-staging --include-crds
```
