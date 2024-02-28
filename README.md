# Open Data Platform

Open Data Platform is composed of open source software for streaming and big data analytic workloads.

![Architecture of Open Data Platform](images/open-data-platform.png)

# Pre-requisite

  * Kubernetes
  * Helm 3.0+

# Configuration

  1. Change passwords in values-secrets.yaml to customized passwords.
  2. Customize configuration settings in values.yaml to optimize data platform.
  3. Customize airflow.externalDatabase.host to match [release]-postgresql hostname.

# Deploy

```
helm install r . -f values-secrets.yaml
```
