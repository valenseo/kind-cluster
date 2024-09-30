# kind-cluster

Configs to create clusters with Kind.

Example: `kind create cluster --name k8s-cluster001 --config cluster-3-nodes.yaml`

"k8s-cluster001" could be any name

Install Ingress:
```
kubectl apply -f ingress-deploy.yaml
```

Example:
```
kubectl apply -f usage.yaml
```

```
curl localhost/foo/hostname
```

```
curl localhost/bar/hostname
```
