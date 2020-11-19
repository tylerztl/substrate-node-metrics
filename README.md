# Substrate Node Metrics
This is a sample for substrate expose metrics and use Prometheus and Grafana
to visualize these metrics.

## Run substrate chain
detailed docs [Create Your First Substrate Chain](https://substrate.dev/docs/en/tutorials/create-your-first-substrate-chain/)

## Start metrics server
```
docker-compose up -d
```

## Visualized dashboard
visit http://127.0.0.1:3000/d/ColmenaLabs/substrate-dashboard?orgId=1&refresh=5s

![metrics](./dashboard.png)
