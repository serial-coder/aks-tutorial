# Azure Kubernetes Services

## Kubernetes

### About Kubernetes
Kubernetes (k8s) is an open-source system for automating deployment, scaling, and management of containerized applications. It groups containers that make up an application into logical units for easy management and discovery.

### Features
1. Start, stop, update, and manage a cluster of machines running containers in a consistent and maintainable way.
2. Particularly suited for horizontally scaleable, stateless, or 'microservices' application architectures.
3. Additional functionality to make containers easier to use in a cluster (reachability and discovery).
4. Kubernetes does NOT and will not expose all of the 'features' of the docker command line.

### Components

1. <b>Master</b>:- It typically consists of </br>
a) kube-apiserver</br>
b) kube-scheduler</br>
c) kube-controller-manager</br>
d) etcd</br>
e) kube-proxy</br>

2. <b>Node</b>:- It typically consists of </br>
a) kubelet</br>
b) kube-proxy</br>
c) cAdvisor</br>

3. <b>Pods</b>:-</br>
a) Single schedulable unit of work which neither move nor spans across machines.</br>
b) Usually one or more container</br>
c) Metadata about the container(s)</br>
d) Env vars – configuration for the container</br>
e) Every pod gets an unique IP by the container engine</br>

![Pods](images/Pods.PNG)
