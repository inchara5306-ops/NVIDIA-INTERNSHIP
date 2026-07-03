# Day 1 – Environment Setup & Kubernetes Basics

## Objective

Set up the GPU development environment and access JupyterLab using a Kubernetes pod.

## Topics Covered

* SSH login using assigned credentials
* Basic Linux terminal commands
* Editing files using `vim`
* Creating and deploying a Kubernetes pod
* Managing pods and services with `kubectl`
* Accessing a running container
* Installing JupyterLab
* Launching JupyterLab with an authentication token
* Connecting through a web browser
* Cleaning up resources by deleting the pod

## Commands Practiced

* `vim pod-service.yaml`
* `kubectl apply -f pod-service.yaml`
* `kubectl get pods`
* `kubectl get services`
* `kubectl exec -it <pod-name> -- bash`
* `pip install jupyterlab`
* `jupyter lab --NotebookApp.token="<token>"`
* `kubectl delete -f pod-service.yaml`

## Outcome

Successfully deployed a Kubernetes pod, configured JupyterLab, accessed the development environment through the browser, and learned basic container lifecycle management.
