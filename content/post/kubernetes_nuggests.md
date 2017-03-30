+++
categories = ['kubernetes', 'borg']
author = "Toby"
title = "I am Locutus of Borg"
featuredalt = "Locutus???"
featuredpath = "/img"
featured = "Locutus.jpeg"
draft = false
description = ""
linktitle = ""
date = "2017-03-30T18:28:57-04:00"

+++

# I am Locutus of Borg

I've been diving head first into the k8s ecosystem over the last month of March 2017.
This is the 2 or 3rd time "diving in" over the last 3 years and this time is the same as the last times.
My experiences have been unpleasant .. here is a running list of the problems i've encountered.

* Every time I want to view the dashboard I get "unauthorized" .. requires you run proxy in some cases

>  https://github.com/kubernetes/kubernetes/issues/31665
>  https://github.com/kubernetes/dashboard/issues/692#issuecomment-260547456

* \<pending\> experience on spark - it always seems like external ip is sitting \<pending\> .. why is this
* Are there any native load balancers or just GCE?
* GCE gets more focus than native and other clouds.. i think this is unfortunate 
* The "Documentation" is all over the map.. old / new .. documention is either nonexistant or very confusing given the frequency of change
* PVC->PV doesn't seem to work with this "missing alpha thing" error
* Adding credetionals for quay.io to .docker/config.json in minikube
* Helm tiller node fails in helm or is overwelmed .. what to do? i ended up getting rid of minikube entirely and starting over
* Container image 'pull's get stuck and minikube needed to be restarted .. happend on quay/stackanetes/mariadb image
* A helm install fails after helm delete.. needed a --purge.. not obvious 

Granted, I'm a relative newbie .. that said, clearly there need some improvements.


