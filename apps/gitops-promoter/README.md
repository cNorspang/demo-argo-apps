# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/demo-argo-apps
# cd into the cloned directory
git checkout 3fd76a419e5e062b0e35bba37d9e2724fdbb478c
helm template . --name-template gitops-promoter --namespace promoter-system --include-crds
```
