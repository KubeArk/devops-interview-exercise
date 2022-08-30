# devops-interview-exercise


# Goal

Create an application that serves a single API endpoint which lists all the pods from a k8s cluster.

# The Task

You are required to provision and deploy a new on-premise kubernetes cluster. It must:

* contain a web application using Flask
* Be publicly accessible(not over the internet since you will be using your own PC to deploy the cluster but from within the same private network), but *only* on port 80. (hint: use MetalLB to expose a private IP to ingress controller)
* list all pods within the k8s cluster on which the application is running by exposing a `/list` endpoint


# Mandatory Work

Fork this repository.

* Provide instructions on how to create the on-premise k8s cluster in a how-to file 

* Provision and manage the application using FluxCD

Give github users `tadrian88|ionut-maxim` access to your fork.
Feel free to ask questions as you go if anything is unclear, confusing, or just plain missing.

# Extra Credit

Expose a second endpoint that takes a parameter called `namespace` and list all pods from within that namespace

# Questions

#### What will you be grading me on?

Python programming skills, elegance, understanding of the technologies you use, security, documentation.

#### Will I have a chance to explain my choices?

Hopefully this will emerge as we pair and converse.
But feel free to comment your code, or put explanations in a pull request within the repo.
