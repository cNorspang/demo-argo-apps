# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/demo-argo-apps
# cd into the cloned directory
git checkout 54afe3fa3b7de9f8f15cfb3ee5f02b669d301727
helm template . --name-template gitops-promoter --namespace promoter-system --values ./apps/gitops-promoter/values/development.yaml --include-crds
```
