# Install Chart

`helm -n metallb-system upgrade --install metallb metallb/metallb -f metallb-values.yaml --create-namespace`

# Test

Test metallb (remember to create namespace):

`kubectl -n test-metallb apply -f https://kind.sigs.k8s.io/examples/loadbalancer/usage.yaml`
