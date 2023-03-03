# go-kubernetes

```Installation ingress-nginx :: Docker Desktop
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.6.4/deploy/static/provider/aws/deploy.yaml
```

```up
kubectl apply -f kubernetes.yml
```

```
curl -X GET http://kp.sing3demons/
```

```
kubectl delete -f .
kubectl delete ns ingress-nginx
```