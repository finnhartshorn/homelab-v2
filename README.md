# homelab-v2

This repository contains all the code to deploy my homelab via [ArgoCD](https://argo-cd.readthedocs.io/en/stable/)

Currently the main shortcoming of this configuration is a lack of secret management, as ArgoCD has no secret management solution by default and I haven't found a plugin tha suits my needs. My homelab is not accessible from outside my network and any sensitive values are mostly defaults so are overridden in the deployed cluster, however secret management would be needed before I considered this config production ready.
