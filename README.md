TO DEPLOY TO KUBERNETES

1. kubectl apply -f reverseproxy_deployment.yaml
2. kubectl apply -f reverseproxy_service.yaml


To change prods
> kubectl get pods


To check services
> kubectl get services


To get details of a particular service
> kubectl describe services