# Docker

This directory contains files and scripts for building custom Docker images that
are used in our demos.

## jenkins-plus

* [`jenkins-plus/`](jenkins-plus/)

Builds the [buoyantio/jenkins-plus](https://hub.docker.com/r/buoyantio/jenkins-plus/)
image, which provides the base jenkins image, along with the kubectl and
namerctl binaries that we need, as well as additional plugins and a
pre-configured pipeline job that we can use to run blue-green deployments. For
more information, see:

* [A Service Mesh for Kubernetes, Part IV: Continuous deployment via traffic shifting](https://blog.buoyant.io/2016/11/04/a-service-mesh-for-kubernetes-part-iv-continuous-deployment-via-traffic-shifting/)

## nginx

* [`nginx/`](nginx/)

Builds the [buoyantio/nginx](https://hub.docker.com/r/buoyantio/nginx/) image,
which provides the base nginx image, along with pre-installed modules that are
useful when using nginx to proxy requests to linkerd. For more information, see:

* [A Service Mesh for Kubernetes, Part V: Dogfood environments, ingress and edge routing](https://blog.buoyant.io/2016/11/18/a-service-mesh-for-kubernetes-part-v-dogfood-environments-ingress-and-edge-routing/)
