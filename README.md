# capi-config

Create a Cluster API management cluster using Microsoft FIPS-enabled images


## How to use this repository

This repository hosts `clusterctl.yaml` and some Kubernetes manifests that it
references. This configuration enables you to create a management cluster that
uses container images for CAPI built by Microsoft instead of the default images
built by the sig-cluster-lifecycle team.

```shell
clusterctl init --config https://raw.githubusercontent.com/mboersma/capi-config/main/clusterctl.yaml
```


## Support

This repository is not officially supported by Microsoft. It is provided as
a convenience to help Cluster API users try out FIPS-enabled images. If you
have questions or problems, please open an issue in this repository.

