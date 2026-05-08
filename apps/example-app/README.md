# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/demo-argo-apps
# cd into the cloned directory
git checkout 6aeb3a958c008d8fc8ae87e6430ec7638710a352
helm template . --name-template example-app --namespace cloud --values ./apps/example-app/values/development.yaml --include-crds
```
