# IAM evaluation
mr checkout
This repository is a collection of tools (Docker containers, Kubernetes Helm Charts, Terraform Configurations) to assist in the evaluation and deployment of Identity and Access Management software in a Higher Education context, focused around Internet2's TIER toolset. It is unofficial and not part of the TIER initiative or endorsed by Internet 2. It is also a work in progress.

The tools are managed in a myrepos (mr) config file. To checkout the tools:

```
git clone git@github.com:mans0954/iam-evaluation.git
mr checkout
```

Repositories:

* [docker/comanage](https://github.com/mans0954/docker-comanage) includes docker-compose file for bringing up comanage, postgres, and IdPs/KDCs for 2 fictitious universities.
* [docker/midpoint](https://github.com/mans0954/docker-midpoint)
* [docker/connid-connector-server](https://github.com/mans0954/docker-connid-connector-server)
* [docker/kerberos](https://github.com/mans0954/docker-kerberos)
* [docker/tier-idp](https://github.com/mans0954/tier-idp)
* [helm/comanage](https://github.com/mans0954/helm-comanage)
* [helm/kerberos](https://github.com/mans0954/helm-kerberos)
* [helm/repo](https://github.com/mans0954/helm-repo) repository for Helm Charts
* [helm/shibboleth-idp](https://github.com/mans0954/helm-shibboleth-idp)
* [helm/iam-evaluation](https://github.com/mans0954/helm-iam-evaluation) requires comanage and shibboleth-idp charts - work in progress
* [terraform/tier-gke](https://github.com/mans0954/terraform-tier-gke) uses terraform to set up Helm in GKE and deploys COmanage helm chart

