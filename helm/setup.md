# Helm Notes

## Steps

1. brew install kubernetes-helm
2. Or download and move helm binary into /usr/local/bin
3. Run helm init to install a local tiller that will also be on Kubernetes cluster

## Helm commands

1. helm upgrade --install $name
2. helm init (this will install tiller on your K8s)
3. helm status
4. helm delete --namespace production  nostromo-narcissus-master-production-nostromo --purge
5. helm upgrade --install jenkins helm/jenkins-k8s/
