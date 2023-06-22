# minikube-argo-cicd

minikube-argo-cicd

```
kubectl set image deploy nginx nginx=nginx:1.14.0
```
```
kubectl rollout status deploy nginx
```

```
kubectl run nginx --image=nginx:alpine
```
```
kubectl port-forward nginx 8080:80
```
                            ^    ^
                            |    |
                            |    |
                External Port  Internal Port
```
http://localhost:8080
```