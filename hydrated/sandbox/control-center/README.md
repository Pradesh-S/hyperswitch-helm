# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout 2302970e2c057a5cf790d3e3e88aac0daa595673
helm template . --name-template test-control-center-hydrator-version-10-prod --include-crds
```
