# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/demo-argo-apps
# cd into the cloned directory
git checkout a3504ebf3fc40bc709d97de7e6ca299d2af8056d
helm template . --name-template gitops-promoter --namespace promoter-system --include-crds
```
