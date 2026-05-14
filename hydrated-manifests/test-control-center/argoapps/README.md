# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout 6508dab31453facfdf406adf1bc54bfdf3a48c9a
helm template . --name-template test-control-center-argo-apps --namespace hyperswitch-sandbox --values ./infra-configurations/prod-values.yaml --include-crds
```
