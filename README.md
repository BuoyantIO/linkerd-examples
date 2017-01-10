# linkerd examples

🎈 Welcome to linkerd-examples! 👋

This repo contains subdirectories with various examples for how to use linkerd
and namerd. Each of the subdirectories is described below.

## Getting started

* [`getting-started/`](getting-started/)

Provides guides for getting linkerd up and running in multiple different
environments, including local development, docker-compose, DC/OS, and
Kubernetes. More information:

* [Getting Started: Running with Docker](https://linkerd.io/getting-started/docker/)
* [Getting Started: Running in Kubernetes](https://linkerd.io/getting-started/k8s/)

## DC/OS

* [`dcos/`](dcos/)

Provides common configurations for deploying linkerd and namerd to DC/OS. More
information:

* [Getting Started: Running in DC/OS](https://linkerd.io/getting-started/dcos/)
* [linkerd on DC/OS for Service Discovery and Visibility](https://blog.buoyant.io/2016/10/10/linkerd-on-dcos-for-service-discovery-and-visibility/)

## Docker

* [`docker/`](docker/)

Contains files and scripts for building custom Docker images that are used in
some of the examples in this repo.

## Failure accrual demo

* [`failure-accrual/`](failure-accrual/)

Provides a self-contained docker-compose environment that can be used to test
various failure accrual settings.

## Gob's microservice

* [`gob/`](gob/)

Defines an example microservice application that uses linkerd and namerd to do
staging, canary, and blue-green deploy.

## http_proxy

* [`http-proxy/`](http-proxy/)

Contains a linkerd configuration file that demonstrates how to make requests
through linkerd using the http_proxy environment variable. More information:

* [Features: HTTP proxy integration](https://linkerd.io/features/http-proxy/)

## A Service Mesh for Kubernetes

* [`k8s-daemonset/`](k8s-daemonset/)

Defines a sample hellow world app and multiple configs for deploying the app
to Kubernetes in various configurations, in support for Buoyant's "A Service
Mesh for Kubernetes" series of blog posts. More information:

* [A Service Mesh for Kubernetes, Part I: Top-Line Service Metrics](https://blog.buoyant.io/2016/10/04/a-service-mesh-for-kubernetes-part-i-top-line-service-metrics/)
* [Getting Started: Running in Kubernetes with DaemonSets](https://linkerd.io/getting-started/k8s-daemonset/)

## Plugins

* [`plugins/`](plugins/)

Contains sample code for building linkerd plugins. More information:

* [In Depth: Plugins](https://linkerd.io/in-depth/plugin/)

## Reqz

* [`reqz/`](reqz/)

Go script that is used to generate traffic to [Gob's microservice](gob/).
