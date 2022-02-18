# kubernative

Kubernetes, or k8s for short, is a system for automating application deployment. Modern applications are dispersed across clouds, virtual machines, and servers. Administering apps manually is no longer a viable option.

K8s transforms virtual and physical machines into a unified API surface. A developer can then use the Kubernetes API to deploy, scale, and manage containerized applications.

Its architecture also provides a flexible framework for distributed systems. K8s automatically orchestrates scaling and failovers for your applications and provides deployment patterns.

It helps manage containers that run the applications and ensures there is no downtime in a production environment. For example, if a container goes down, another container automatically takes its place without the end-user ever noticing.

Kubernetes is not only an orchestration system. It is a set of independent, interconnected control processes. Its role is to continuously work on the current state and move the processes in the desired direction.

## Architecture with Diagrams: 

Kubernetes has a decentralized architecture that does not handle tasks sequentially. It functions based on a declarative model and implements the concept of a ‘desired state.’ These steps illustrate the basic Kubernetes process:

-> An administrator creates and places the desired state of an application into a manifest file.
The file is provided to the Kubernetes API Server using a CLI or UI. Kubernetes’ default command-line tool is called kubectl. In case you need a comprehensive list of kubectl commands, check out our Kubectl Cheat Sheet.

-> Kubernetes stores the file (an application’s desired state) in a database called the Key-Value Store (etcd).

-> Kubernetes then implements the desired state on all the relevant applications within the cluster.

-> Kubernetes continuously monitors the elements of the cluster to make sure the current state of the application does not vary from the desired state.

![ScreenShot](https://github.com/kumarrkslinux/kubernative/blob/main/Architecture%20with%20Diagrams.PNG)


Certified Kubernetes Administrator: https://www.cncf.io/certification/cka/

Exam Curriculum (Topics): https://github.com/cncf/curriculum

Candidate Handbook: https://www.cncf.io/certification/candidate-handbook

Exam Tips: http://training.linuxfoundation.org/go//Important-Tips-CKA-CKAD

