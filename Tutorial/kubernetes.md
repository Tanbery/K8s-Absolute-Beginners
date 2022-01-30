# Kubernetes Commands

```yml
kubectl get all
kubectl create -f <filename>.yaml --record
kubectl apply -f <filename>.yaml

kubectl get replicaset
kubectl get pods -o wide

kubectl delete pod <pod_name>

kubectl scale replicaset <replica-name> --replicas=2
kubectl scale deployment <deploy-name> --replicas=2


kubectl rollout undo <deplyment name>
kubectl rollout status
kubectl rollout history

minikube service <service-name> --url
```
