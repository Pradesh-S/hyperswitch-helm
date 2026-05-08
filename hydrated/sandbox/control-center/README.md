# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout dacc3af7b8cb0e7c2b4531cf5cb4ae25af022bb3
helm template . --name-template test-control-center-hydrator-version-10f --include-crds
```
