# Kubernetes

minikube start --driver=docker # Minikube étant un Kubernetes local (simulation de cluster)

kubectl apply -f .\nginx-demo.yaml

kubectl get pod

kubectl get replicaset

kubectl describe pod nginx-demo

kubectl exec -it nginx-demo-675d657bcd-6f7mg -- sh

kubectl get service
kubectl describe service nginx-service
