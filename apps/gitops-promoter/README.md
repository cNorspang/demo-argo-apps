# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/demo-argo-apps
# cd into the cloned directory
git checkout fa6ab672fd18992ea2e0719b0c1190ababc1f4c8
helm template . --name-template gitops-promoter --namespace promoter-system --include-crds
```
