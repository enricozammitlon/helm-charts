## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add kube-plex https://enricozammitlon.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
rico` to see the charts.

To install the kube-plex chart:

    helm install kube-plex rico/kube-plex

To uninstall the chart:

    helm delete kube-plex