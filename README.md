<h1 align="center"> Kubernetes training </h1>
Repository to be used as reference in Kubernetes training

<h3> How to start? </h3>
We can use the Play with Kubernetes, which is a kubernetes playground in the browser provided by Docker and created by Tutorius. 
![play](https://imgur.com/RU6ODjn)

Run the following commands in [Play with Kubernetes](https://labs.play-with-k8s.com/) terminal:


```
kubeadm init --apiserver-advertise-address $(hostname -i) --pod-network-cidr 10.5.0.0/16
```

```
kubectl apply -f https://raw.githubusercontent.com/cloudnativelabs/kube-router/master/daemonset/kubeadm-kuberouter.yaml
```

Enjoy your cluster!
