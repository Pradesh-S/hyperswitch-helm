# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout e1cfdbffec82468a177949a9bf9e9fe1cbff2f4e
helm template . --name-template control-center-staging --include-crds
```
