# openshift-dockercoin

Attempt to implement @jpetazzo  Dockercoin on Openshift.
[Orchestration Workshop](https://jpetazzo.github.io/orchestration-workshop/#).

See https://github.com/jpetazzo/dockercoins.git

* https://github.com/gloppasglop/openshift-dockercoin-rng.git
* https://github.com/gloppasglop/openshift-dockercoin-hasher.git
* https://github.com/gloppasglop/openshift-dockercoin-worker.git
* https://github.com/gloppasglop/openshift-dockercoin-webui.git


Openshift Setup
---------------

### Installation

Check for detailed installation instruction on.

If you have a system with a Docker engine installed, the simplest way to get a running Openshift environment is to download the client tools from the [releases page](https://github.com/openshift/origin/releases) and place the oc binaries in your PATH.

You can then run `oc cluster up` to get started immediately. 


### Upload Dockercoin template


```
# Load temmplate
oc create -f dockercoin.yaml
```



