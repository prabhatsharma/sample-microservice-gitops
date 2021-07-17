# Sample gitops

Uses kustomize

base code repo is at: https://github.com/prabhatsharma/sample-microservice

Build commands:

- dev build - kustomize build  overlays/dev
- test build - kustomize build  overlays/test
- prod build - kustomize build  overlays/prod

