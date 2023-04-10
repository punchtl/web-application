# web-application

Применить манифест
```
kubectl apply -f php-apache.yaml
```

Автомасштабирование
```
kubectl autoscale deployment php-apache --cpu-percent=60 --min=1 --max=4
```

https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale-walkthrough/
