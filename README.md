# applications

This repo holds Kubernetes resources to be recursively synced by ArgoCD. There is an app-of-apps for the following environements:

- Parent app-of-apps name: `apps-staging`, applications branch name: `staging`
- Parent app-of-apps name: `apps-production`, applications branch name: `main` (not yet implemented)
- Parent app-of-apps name: `apps-testing`, applications branch name: `testing` (not yet implemented)
