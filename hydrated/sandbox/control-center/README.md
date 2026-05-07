# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout 82fb5d58d0fb902067e423ed751be6c8298b0e43
helm template . --name-template test-control-center-hydrator-version-10b --include-crds
```
