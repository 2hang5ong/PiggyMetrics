# PiggyMetrics helm chart


Run kompose to create helm chart from docker-compose file

```
tmp $ export NOTIFICATION_SERVICE_PASSWORD=passw0rd
tmp $ export CONFIG_SERVICE_PASSWORD=passw0rd
tmp $ export STATISTICS_SERVICE_PASSWORD=passw0rd
tmp $ export ACCOUNT_SERVICE_PASSWORD=passw0rd
tmp $ export MONGODB_PASSWORD=passw0rd
tmp $ kompose convert -f docker-compose.yml -o piggymetrics -c
```

Update chart, add default password in [values.yaml](piggymetrics/values.yaml) file

