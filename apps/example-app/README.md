# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/demo-argo-apps
# cd into the cloned directory
git checkout 8370a020f78070d72daf199717100b384d03d0c2
helm template . --name-template example-app --namespace cloud --include-crds
```
