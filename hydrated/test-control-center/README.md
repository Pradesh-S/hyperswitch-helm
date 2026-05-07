# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout f36c098ac27eb483d68149943a672497541ecfd9
helm template . --name-template test-control-center-hydrator --include-crds
```
