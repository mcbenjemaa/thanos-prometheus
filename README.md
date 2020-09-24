# prometheus-thanos


### Install Prometheus

```
helm install -n monitoring --values prometheus-values.yaml prometheus charts/prometheus
```


### Install Thanos 
```
helm install -n monitoring --values thanos-values.yaml thanos charts/prometheus-thanos
```





### Install Sealed-Secrets
```
helm install -n kube-system --values sealed-secret-values.yaml sealed-secrets charts/sealed-secrets
```
