
GitOps repo for demo App-of-Apps (dev/stage/prod)

- Root App-of-Apps -> cluster/<env>/root-app.yaml
- Per-app Argo CD Application -> cluster/<env>/apps/*.yaml
- App manifests under apps/demo-app/{base,overlays}
- CI workflows live in .github/workflows (update-dev.yml, promote workflows)
