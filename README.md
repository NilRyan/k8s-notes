## Kubernetes Architecture

Each server in a Kubernetes cluster gets a role:
1. control-plane — Makes most of the necessary decisions and acts as sort of the brains of the entire cluster. This can be a single server or a group of server in larger projects. 
2. node — Responsible for running workloads. These servers are usually micro managed by the control plane and carries out various tasks following supplied instructions.
