# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/demo-argo-apps
# cd into the cloned directory
git checkout 4bde3999d7f0c17693070891576f0baa649712a1
helm template . --name-template example-app --namespace cloud --values ./apps/example-app/values/development.yaml --include-crds
```
