# Open Data Platform

Open Data Platform is composed of open source software for streaming and big data analytic workloads.

# Pre-requisite

  # Kubernetes
  # Helm 3.0+

# Configuration

  # Change passwords in values-secrets.yaml to customized passwords.
  # Customize configuration settings in values.yaml to optimize data platform.
  # Customize airflow.externalDatabase.host to match [release]-postgresql hostname.

# Deploy

```
helm install r . -f values-secrets.yaml
```
