## Kubernetes for ML Engineers
### What is this repo about?
This is a step by step guide to help you understand the basics of Kubernetes.

You will learn how to build and deploy a containerized app (in this case, a simple FastAPI app) to a Kubernetes cluster.

Because I want you to become a Real World ML/MLOps Ninja.

Let's get started.
### Install the tools
1. uv to create the project and manage the dependencies.
2. Docker to build and run docker images, including the nodes of the kind cluster.
3. Kind to create a local Kubernetes cluster.
4. kubectl to interact with the Kubernetes cluster.
2. Create a local Kubernetes cluster
We will use kind to create a local Kubernetes cluster. It will be a simple cluster that will run entirely on your machine, using as Kubernetes nodes simple Docker containers.

A local cluster like the one we are creating here is useful for development and CI pipelines, where you need a minimal cluster to run integration tests for your applications.


