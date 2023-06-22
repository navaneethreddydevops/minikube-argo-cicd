# minikube-argo-cicd

minikube-argo-cicd

```bash
kubectl set image deploy nginx nginx=nginx:1.14.0
```

```bash
kubectl rollout status deploy nginx
```

```bash
kubectl run nginx --image=nginx:alpine
```

```bash
kubectl port-forward nginx 8080:80
```

                            ^    ^
                            |    |
                            |    |
                External Port  Internal Port

```bash
http://localhost:8080
```
