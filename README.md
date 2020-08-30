# helm-influxdb

## render
```shell script
helm template helm-influxdb > influxdb.yml
```

## port-forward
```shell script
kubectl port-forward --namespace influxdb svc/influxdb 8086
```