# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout dc2bfc1cd08b5c5c29dd0c11ddc33446e709a0bf
helm template . --name-template test-control-center-hydrator-prod-version --namespace hyperswitch-prod --values ./charts/incubator/hyperswitch-control-center/helm-sandbox-values.yaml --include-crds
```
