# nordmart-infra-gitops-config

Global/common/cluster scoped resources are deployed via this gitops config repository

We have 2 clusters:

1. Cluster # 1 (i.e. dev-test) 
2. Cluster # 2 (i.e. stage-prod) 

## Application workloads

The environment scoped application resources are deployed through [nordmart-apps-gitops-config](https://github.com/stakater/nordmart-apps-gitops-config) repository. 
