# quarkus-hello-world-deployment

## Branches: helm  

Each of the following branches contained the source of truth of what is must be deployed in the platform for the following kind of environment:

- development

- staging

- production

## Branch: kustomize

The 'kustomize' branch contains how to obtain same results when deploying the applications as in the "helm branches" mentioned above. In this case, regular k8s objects and simple kustomize overlays are used per environment.
