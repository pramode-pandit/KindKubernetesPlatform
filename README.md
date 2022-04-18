### Kind Kubernetes Platform

#### Quickstart
-- installing kind from release binaries
  > https://kind.sigs.k8s.io/docs/user/quick-start/#installing-from-release-binaries


#### 1. create a kubernetes cluster

```
kind create cluster --name insight --config kind-config.yaml
```

#### 2. verify the kubernetes cluster.

```
kind get clusters
```

#### 3. connect kubectl to new cluster

```
kubectl cluster-info --context kind-insight
```
