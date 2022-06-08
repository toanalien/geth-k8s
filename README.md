# geth-k8s

```bash
kubectl apply -f admin.yaml
kubectl apply -f geth.yaml
kubectl apply -f service.yaml
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.1.1/deploy/static/provider/do/deploy.yaml
kubectl apply -f ingress.yaml
```
