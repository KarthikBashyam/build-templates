# Build Templates
This repo contains all reusable knative build templates used in Storefinder service

## Deploy to K8s
Run command below to deploy the template to your k8s cluster. Be sure to install the Knative build components as pre-requisite

```

kubectl apply -f https://raw.githubusercontent.com/storefinder/build-templates/master/ci-build-template.yaml

```