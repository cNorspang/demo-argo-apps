# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/cNorspang/demo-argo-apps
# cd into the cloned directory
git checkout 4e2142136b3f32818a11f44a593f61c3b3cb11e9
helm template . --name-template example-app --namespace cloud --values ./apps/example-app/values/development.yaml --include-crds
```
