# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout b47b42b1a1c302ecb1f0134354bab83c1548cf22
helm template . --name-template test-control-center-hydrator --include-crds
```
