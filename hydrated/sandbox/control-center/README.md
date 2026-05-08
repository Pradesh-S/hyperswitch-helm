# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout ed1608099a28f75d4b83c1554591e5667c23b146
helm template . --name-template test-control-center-hydrator-version-10g --include-crds
```
