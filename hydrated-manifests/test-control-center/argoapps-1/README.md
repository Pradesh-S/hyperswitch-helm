# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone git@github.com:Pradesh-S/hyperswitch-helm.git
# cd into the cloned directory
git checkout a1a90de1c180e58fb0badad2fe7395d5e795599c
helm template . --name-template test-control-center-argo-apps --namespace hyperswitch-sandbox --values ./infra-configurations/sandbox-values.yaml --include-crds
```
