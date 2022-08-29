minikube addons enable ingress
kubectl patch deployments ingress-nginx-controller -n ingress-nginx --patch-file ingress-path.yaml
helm install dz3 ./dz3


все запросы в коллекции postman