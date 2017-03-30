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

I've been diving head first into kubernetes over the last month of March 2017.
This is the 2 or 3rd time diving in over the last 2 years and this time is the same as the last.
My experiences so far have been unpleasant .. here is a running list of the problems i've encountered.
Now granted, I'm still a relative newbie but clearly there needs improvements.

- every time I want to view the dashboard I get "unauthorized" .. requires you run proxy in some cases
   https://github.com/kubernetes/kubernetes/issues/31665
- <pending> experience on spark - it always seems like external ip is sitting <pending> .. why is this
- are there any native load balancers or just GCE?
- GCE gets more focus than native and other clouds.. i think this is unfortunate 
- documentation all over the map.. old / new . generally the documention is either nonexistant or very confusing given the frequency of change.
- PVC->PV doesn't seem to work with this "missing alpha thing" error
- adding credetionals for quay.io to .docker/config.json in minikube
- tiller node fails in helm or is overwelmed .. what to do? i ended up getting rid of minikube entirely and starting over
- 'pull' gets stuck and minikube needed to be restarted .. happend on quay/stackanetes/mariadb image
- helm install fails after helm delete.. needed a --purge.. not obvious 



