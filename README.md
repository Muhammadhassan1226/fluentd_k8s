# Introduction to Fluentd on Kubernetes
## Prerequisites 
You will need a basic understanding of Fluentd before you attempt to run it on Kubernetes.<br/> 
Fluentd and Kubernetes have a bunch of moving parts.<br/> 
A Kubernetes Cluster .<br/>
The most important components to understand is the fluentd `tail` plugin. <br/>
This plugin is used to read logs from containers and pods on the file system and collect them.


## Fluentd Manifests

I would highly recommend to use manifests from the official fluentd [github repo](https://github.com/fluent/fluentd-kubernetes-daemonset) for production usage <br/>

The manifests found here are purely for demo purpose. <br/>
The manifests in this repo are broken down and simplified for educational purpose. </br>
<br/>


