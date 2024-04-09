# GitOps Examples

This repository contains examples on GitOps with [ArgoCD](https://argo-cd.readthedocs.io)
to try out and build upon.

It explores the following concepts:

- basic ArgoCD `Applications`, using the manifests in [`first-gitops-app/`](./first-gitops-app)
- a simple _App-of-Apps_ `Application`, using [`parent-app.yaml`](./parent-app.yaml) and the children `Applications` in [`apps/`](./apps)
- an example `ApplicationSet`, using [`monitoring-appset.yaml`](./monitoring-appset.yaml) and the directories under [`monitoring-appset/`](./monitoring-appset/)

For `parent-app.yaml` and `monitoring-appset.yaml`, only boilerplate YAML is defined - all information regarding the actual ArgoCD environment, repositories, etc. need to be entered.
