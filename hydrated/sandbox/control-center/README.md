# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout dc2bfc1cd08b5c5c29dd0c11ddc33446e709a0bf
helm template . --name-template test-control-center-hydrator-sandbox-version --namespace hyperswitch-sandbox --include-crds
```
