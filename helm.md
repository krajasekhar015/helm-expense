# HELM CHARTS

Helm Charts are a way to define, install, and manage Kubernetes applications. **Helm is a package manager for Kubernetes, and Helm Charts are the "packages" that Helm uses to deploy applications or services onto a Kubernetes cluster.**

Generally we have two steps for docker and kubernetes. They are: 
1. image creation -> Dockerfile 
2. How to run image -> Docker compose/manifest

First thing here that image should exist physically. If image exits, then we can tell kubernetes how to run the image with different options like deployment, statefulset, pod, replicaset, how many number of replicas required, how many resources etc., through manifest file. 

- Polpular tools have opensource images and also opensource manifest

**Usage of Helm Charts**
- We can use helm charts to templatise manifest files 
- To install custom or popular applications in kubernetes like CSI drivers, Metrics Server, Prometherus/Grafana 

