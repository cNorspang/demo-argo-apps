# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/demo-argo-apps
# cd into the cloned directory
git checkout ec7a257510cb094314a860eb24d93c8ab266ac4c
helm template . --name-template gitops-promoter --namespace promoter-system --include-crds
```
