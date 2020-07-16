# kubernetes

<img src="kubernetes_logo.png" width="96">

[Kubernetes](https://kubernetes.io/) is a container-orchestration system.
It provides a platform for automating deployment, scaling, and operations of application containers across clusters of hosts. It works with a range of container tools, including Docker.

[Helm](https://helm.sh/) is increasingly becoming a standard way for managing applications on Kubernetes. The easiest way to think about Helm is as a package manager for Kubernetes. More details here: [Deploying the ELK Stack on Kubernetes with Helm](https://logz.io/blog/deploying-the-elk-stack-on-kubernetes-with-helm/)

[Kubernetes network-plugins](https://kubedex.com/kubernetes-network-plugins/): Differences between Flannel, Calico, Weave, Cilium, Kube Router, Romana and Contiv.

## machine learning & kubernetes
[Dask Kubernetes](https://kubernetes.dask.org/en/latest/): Dask Kubernetes deploys Dask workers on Kubernetes clusters using native Kubernetes APIs and it is designed for deployments of workers during the lifetime of a Python process.

[Machine Learning im Kubernetes-Cluster](https://m.heise.de/developer/artikel/Machine-Learning-im-Kubernetes-Cluster-4226233.html?seite=all). Heise-Artikel

[Kubeflow](https://medium.com/kubeflow/kubeflow-1-0-cloud-native-ml-for-everyone-a3950202751) is a Cloud Native platform for machine learning based on Google’s internal machine learning pipelines.

[Kubeflow - Github](https://github.com/kubeflow/kubeflow)

## other basic links
[training material](https://github.com/loodse/k8s-exercises/tree/master/containers/fundamentals)

[how to log](https://github.com/loodse/k8s-exercises/blob/master/containers/fundamentals/10_logs.md)

## docker links
[docker hub official](https://hub.docker.com/search?q=&type=image)  

[dockerfile best practices](https://youtu.be/JofsaZ3H1qM)

[docker samples](https://docs.docker.com/samples/)

[docker playground](https://labs.play-with-docker.com)

my docker hub
<a href="https://hub.docker.com/u/thehadz" alt="my docker account">
  <img src="docker_logo.png" align="left" width="96" >
</a>

<br>
<br>
<br>
<br>

## examples
[flask application as container](https://github.com/hadze/kubernetes/tree/master/flask)

[Kubernetes Guestbook Example](https://github.com/loodse/k8s-exercises/tree/master/k8s/fundamentals/kubernetes_example): Based on the Kubernetes tutorial this example will show how a multi-tier web application is built and deployed to a Kubernetes cluster. It consists of Redis as a database backend and a PHP guestbook. Redis will get a single-instance master to store the entries together with multiple replicated instances for reading. The guestbook will run on multiple frontend instances.
