<div style="float: right;"><img src="../../images/01.png" width="160px" /></div><br>


# Overview

<center>

  ![](./../../images/07.png)

</center>

[**Container Storage Interface (CSI)**](https://kubernetes-csi.github.io/docs/) is a standardized specification for exposing arbitrary block and file storage systems to containerized workloads in orchestrators like Kubernetes. The **vContainer Storage Interface** extends the capabilities of **VNG CLOUD storage service** to seamlessly integrate with container orchestration platforms, providing dynamic and scalable storage solutions for containerized applications.

Key features of the **vContainer Storage Interface** include:

|#|Feature|Description|
|-|-|-|
|1|**Dynamic provisioning**|The **vContainer Storage Interface** plugin enables on-demand creation of **Persistent Volumes** for containerized workloads. This enhances the agility and scalability of container deployments by allowing storage resources to be provisioned automatically based on workload requirements.|
|2|**Block volume**|The plugin supports **Block Volume** storage, which is ideal for applications that require high performance and low latency storage solutions.|
|3|**Volume expansion**|Driver supports both **Offline** _(volume is currently not published or available on a node)_ and **Online** _(volume is currently published or available on a node)_ resize of volumes.<br><br>This capability ensures that storage resources can scale in tandem with the evolving demands of applications, providing a responsive and adaptable infrastructure.|