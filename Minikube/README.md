Minikube setup on Ubuntu 22.04, 20.04, 18.04, 16.04

Create an Ubuntu Ece machine t3.micro, minimum memory 1800 MiB

Refer below pages.

https://medium.com/@areesmoon/installing-minikube-on-ubuntu-20-04-lts-focal-fossa-b10fad9d0511   --- minikube installation
https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/   --- Kubectl installation

![image](https://github.com/AmbroseShallet/Kubernetes_Shallet/assets/155511260/db87fe5d-25e0-425f-b888-17d28965414b)

![image](https://github.com/AmbroseShallet/Kubernetes_Shallet/assets/155511260/60e92efa-a999-4392-865d-9a8811ae6ec6)

![image](https://github.com/AmbroseShallet/Kubernetes_Shallet/assets/155511260/03b935d3-10eb-49ee-90f3-8b11a632d841)



Start minikube

switch to ubuntu user because docker driver should not be used with root privileges.
Give full permission to /var/docker/docker.sock if getting permission related error. 
minikube start -driver=docker
