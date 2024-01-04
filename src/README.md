<center>

  ![](./images/01.png)

</center>


![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=Helm&labelColor=0F1689) ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![Github Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white) ![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

![production-env](https://badgen.net/badge/PRODUCTION/environment/blue?icon=github)
# Introduction

The **vContainer Helm Infra** repository houses **Helm Charts** designed to enhance functionalities for **vContainer Kubernetes clusters**.

These **Helm charts** seamlessly integrate with the infrastructure and services offered by **VNG CLOUD**. Through the **VNG CLOUD portal**, customers can efficiently oversee the resources of their vContainer Kubernetes clusters. The currently supported Helm charts include:

|#|Chart name|Description|Artifact/Github repository|
|-|-|-|-|
|1|[`vcontainer-storage-interface`](./helm-charts/vcontainer-storage-interface/index.md)|Provides `PersistentVolume` for **vContainer Kubernetes clusters**.|- **Artifact**: [https://artifacthub.io/packages/helm/vcontainer-helm-infra/vcontainer-storage-interface](https://artifacthub.io/packages/helm/vcontainer-helm-infra/vcontainer-storage-interface)<br>- **GitHub**: [https://github.com/vngcloud/vcontainer-storage-interface](https://github.com/vngcloud/vcontainer-storage-interface)|

# Installation
## Prerequisites
- Helm 3.0+, see [Installing Helm](https://helm.sh/docs/intro/install/).
- `kubeconfig` file of the **vContainer Kubernetes cluster**, see [Use Kubeclt to access the Container that was initialized at](https://docs.vngcloud.vn/display/VSERVERENG/Step+3%3A+Use+Kubeclt+to+access+the+Container+that+was+initialized+at).

## Install the `vcontainer-helm-infra` repository
To install the **vContainer Helm Infra** repository, use the following command:
  ```bash
  helm repo add vcontainer-helm-infra https://vngcloud.github.io/vcontainer-helm-infra
  helm repo update
  ```

<center>

  ![](./images/12.png)

</center>

# Uninstall the **vContainer Helm Infra** repository
- To completely remove the **vContainer Helm Infra** repository, use the following command:
```bash=
helm repo remove vcontainer-helm-infra
```

<center>

  ![](./images/16.png)

</center>
