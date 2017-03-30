+++
categories = []
author = ""
featuredpath = ""
title = "kubernetes_nuggests"
draft = true
description = ""
featuredalt = ""
featured = ""
linktitle = ""
date = "2017-03-29T15:13:45-04:00"

+++

I've been diving heavy into kubernetes over the last month of March 2017.
My experiences so far have been unpleasant .. here is a running list of the problems i've encountered.

- "unauthorized" experience
   https://github.com/kubernetes/kubernetes/issues/31665
- <pending> experience on spark
- load balancers native or just GCE?
- GCE gets more focus than native and other clouds.. bad
- documentation all over the map.. old / new 
- PVC->PV doesn't seem to work "alpha" error
- adding credetionals for quay.io to .docker/config.json in minikube
- tiller node fails in helm or is overwelmed .. what to do?
- 'pull' gets stuck and minikube needed to be restarted .. happend on quay/stackanetes/mariadb image
- helm install fails after helm delete.. needed a --purge.. not obvious 

Generally the documention is either nonexistant or very confusing given the frequency of change.


