# Cloud Native PostgreSQL Helm Chart

Helm chart to install the
[Cloud Native PostgreSQL operator](https://docs.enterprisedb.io/cloud-native-postgresql/),
designed by EnterpriseDB to manage PostgreSQL workloads on any
supported Kubernetes cluster running in private, public, or hybrid cloud
environments.

## Deployment

To deploy the operator from sources you can run the following command:

```console
helm upgrade --install cnp \
  --namespace postgresql-operator-system \
  --create-namespace \
  cloud-native-postgresql
```

## Copyright

`cloud-native-postgresql-helm` is distributed under Apache License 2.0.

**IMPORTANT:** Both the operator and the operand images are distributed
under different license terms, in particular the Cloud Native PostgreSQL
operator is distributed under the
[EnterpriseDB Limited Use License](https://www.enterprisedb.com/limited-use-license).

Copyright (C) 2021 EnterpriseDB Corporation.