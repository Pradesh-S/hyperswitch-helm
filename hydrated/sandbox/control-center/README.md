# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout e1cfdbffec82468a177949a9bf9e9fe1cbff2f4e
helm template . --name-template test-control-center-hydrator-simple --include-crds
```
