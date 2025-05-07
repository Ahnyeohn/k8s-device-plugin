# NVIDIA device plugin for Kubernetes
this repository is a custom version for NVIDIA device plugin for Kubernetes
the original repo is at https://github.com/NVIDIA/k8s-device-plugin

# NVIDIA device plugin for MPS enable
original device plugin is only supports evenly split MPS.
Also, each Pod cannot request more than 2 resources.

To figure out these issue, some source codes are fixed
