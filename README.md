# kubes-my-health
In this ‘how-to’ guide, we’re going to create an instance of the IBM Kubernetes Service (IKS) in the IBM Cloud, connect to it and then deploy an application to it, via a Container Registry, also in the IBM Cloud.

The application we’re going to use is a simple Node.js application called “Example Health”. This is a sample UI program for a patient health system and it is available in the following GitHub repository: https://github.com/IBM/node-s2i-openshift.

The steps we’re going to take are broadly as follows:

1)	Create the Kubernetes Cluster
2)	Install the software and tools needed to complete the deployment from your local machine
3)	Build a container
4)	Push the container to a repository
5)	Deploy and expose the application on your Kubernetes cluster

Depending on your level of expertise and what you already have deployed on your local machine, this can take a couple of hours or more to compete. 

This guide may be updated from time to time, to reflect changes in the service as and when they arise.

