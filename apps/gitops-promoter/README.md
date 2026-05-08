# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/demo-argo-apps
# cd into the cloned directory
git checkout cd324d36a94e591e6626443696f4be27634cfe3f
helm template . --name-template gitops-promoter --namespace promoter-system --include-crds
```
