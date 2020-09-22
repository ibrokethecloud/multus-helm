## multus-helm

Simple helm chart to install multus damoneset to your cluster.

Minor tweak to upstream manifest to include an init container to extra the containernetworking/plugin binaries to /opt/cni/bin
