### NodePort-Service

kubectl create -f service.yaml

kubectl get services

curl hhtp:/192.168.1.2:30008


### ClusterIP-Service

kubectl create -f service-clusterip.yaml

kubectl get services

curl hhtp:/192.168.1.2:30008


### Loadbalancer-Service

