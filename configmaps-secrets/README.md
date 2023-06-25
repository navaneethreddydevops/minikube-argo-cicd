# config maps commands:

```bash
kubectl create configmap new-config-map --from-file=settings
```

```bash
kubectl create configmap new-config-map --from-env-file=env.settings
```

```bash
kubectl create -f nginx-configmap.yaml
```
