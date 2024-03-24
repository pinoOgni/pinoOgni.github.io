---
title: "Polycube and gRPC"
image: "images/portfolio/polycube_grpc.jpg"
categories: ["C++","gRPC"]
description: "Polycube framework and gRPC"
draft: false
---


[polycube-grpc-service-libraries](https://github.com/pinoOgni/polycube-grpc-service-libraries) allow the writing of a stand-alone Polycube service also in other languages.

Polycube services, called cubes, can be composed to build arbitrary service chains and provide custom network connectivity to namespaces, containers, virtual machines, and physical hosts.

#### My work in brief

I have created an architecture that allows the creation of network services in Polycube using languages such as GO, Python, C++ and other languages supported by gRPC. GRPC was chosen because it offers the possibility of running the controlplane part of a service even on a remote machine, different from where the dataplane is run. The work done would make it easier to get more developers to the Polycube open-source project.

I had to deal with various interesting concepts such as long-lived-streaming grpc calls and with the creation of services in Polycube in other languages besides C++.

You can find the code [here](https://github.com/pinoOgni/polycube-grpc-service-libraries).
I'm no longer active in the development of polycube-grpc-service-libraries an probably some documentation and some comments are missing. I still hope there is enough.