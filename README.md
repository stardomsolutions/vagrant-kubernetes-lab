# vagrant-kubernetes-lab
This project is to provide a simple local Kubernetes cluster with a master and a worker node for testing purpose.

Vagrant was chosen for being able to create the cluster either on linux, windows and mac hosts.

## Prequirements
- Vagrant : https://www.vagrantup.com/downloads.html
- VirtualBox : https://www.virtualbox.org/wiki/Downloads

## Default provisioning
Vagrant up will provide 2 Ubuntu Xenial VMs for a kubernetes cluster with these features by default :
- Kubernetes control plane (latest)
- Weave network cni (latest)
- Kubernetes Dashboard (latest)
- Heapster v1.5.1
- Helm (latest)
