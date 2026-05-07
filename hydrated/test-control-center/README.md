# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout e849da104136ddd70643b11553762efc8913355c
helm template . --name-template test-control-center-hydrator --include-crds
```
