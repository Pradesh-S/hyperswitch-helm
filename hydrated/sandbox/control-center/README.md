# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout f85783681b4b70430f47a160e93e80c24a4924fd
helm template . --name-template test-control-center-hydrator-version-10c --include-crds
```
