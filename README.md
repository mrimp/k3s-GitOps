<div align="center">

<img src="https://camo.githubusercontent.com/5b298bf6b0596795602bd771c5bddbb963e83e0f/68747470733a2f2f692e696d6775722e636f6d2f7031527a586a512e706e67" align="center" width="144px" height="144px"/>

### My home Kubernetes cluster :sailboat:
### GitOps Workflow for Kubernetes Cluster:

_... managed with Flux and Renovate_ :robot:

</div>

<br/>

<div align="center">

[![k3s](https://img.shields.io/badge/k3s-v1.21.2-brightgreen?style=for-the-badge&logo=kubernetes&logoColor=white)](https://k3s.io/)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white&style=for-the-badge)](https://github.com/pre-commit/pre-commit)
[![renovate](https://img.shields.io/badge/renovate-enabled-brightgreen?style=for-the-badge&logo=renovatebot&logoColor=white)](https://github.com/renovatebot/renovate)
  
</div>

<div align="center">
  
[![Home-Internet](https://img.shields.io/uptimerobot/status/m789505035-c112a2c8baa014b335cd2dc6?color=important&label=home%20internet&style=flat-square&logo=opnSense&logoColor=white)](https://uptimerobot.com)
[![My-Plex](https://img.shields.io/uptimerobot/status/m789505035-c112a2c8baa014b335cd2dc6?logo=plex&logoColor=white&color=important&label=my%20plex&style=flat-square)](https://plex.tv)

</div>

## :wrench:&nbsp; Workloads (by namespace)

* [cert-manager](https://github.com/jetstack/cert-manager)
* [flux-system-extra](https://github.com/fluxcd/flux2/)
* [kube-system](https://kubernetes.io/docs/concepts/overview/components/)
* [logs](logs/)
* [monitoring](monitoring/)
* [rook-ceph](rook-ceph/)
* [system-upgrade](system-upgrade/)

## :robot:&nbsp; Automation

* [Renovate](https://github.com/renovatebot/renovate) keeps workloads up-to-date by scanning the repo and opening pull requests when it detects a new container image update or a new helm chart
- [System Upgrade Controller](https://github.com/rancher/system-upgrade-controller) automatically upgrades k3s to new versions as they are released


---

## :book:&nbsp; Overview

![k3s Nodes](https://i.imgur.com/MmEfXeu.png)

This is home to my personal Kubernetes cluster. [Flux](https://github.com/fluxcd/flux2) watches this Git repository and makes the changes to my cluster based on the manifests in the [cluster](./cluster/) directory. [Renovate](https://github.com/renovatebot/renovate) also watches this Git repository and creates pull requests when it finds updates to Docker images, Helm charts, and other dependencies.

![rancher](https://i.imgur.com/o1DMXE4.png)

Rancher is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

A little Rancher Grafana Eye Candy...

![grafana](https://i.imgur.com/ofSFE6m.png)


## :handshake:&nbsp; Community

There is a really great community of like-minded folks doing similar efforts who have shared their clusters over at [awesome-home-kubernetes](https://github.com/k8s-at-home/awesome-home-kubernetes)

There is also an active the k8s@home [Discord](https://discord.gg/7PbmHRK) for this community and great discussion.

Thanks to all the people who donate their time to the [Kubernetes @Home](https://github.com/k8s-at-home/) community.

