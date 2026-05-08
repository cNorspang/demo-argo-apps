# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/demo-argo-apps
# cd into the cloned directory
git checkout 3d7fe4c2bdb3692ee16ded482f0e7b03112f3f4c
helm template . --name-template gitops-promoter --namespace promoter-system --include-crds
```
