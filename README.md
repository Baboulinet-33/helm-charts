# helm-charts

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/baboulinet)](https://artifacthub.io/packages/search?repo=baboulinet)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add baboulinet-33 https://baboulinet-33.github.io/helm-charts/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
baboulinet-33` to see the charts.

To install the <chart-name> chart:

    helm install my-<chart-name> baboulinet-33/<chart-name>

To uninstall the chart:

    helm delete my-<chart-name>

The charts are tested and validated on OpenShift

## Charts available:
- swagger
- pgrest
- krakend openshift