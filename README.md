### Monitor redis in grafana
This repository provides a setup to monitor Redis using Grafana, whether in cluster mode or non-cluster mode.
i use this dashboard link

## Dashboard
You can use the following Grafana dashboard for monitoring Redis:
- Dashboard Link - [Grafana Dashboard for Redis](https://grafana.com/grafana/dashboards/12776-redis/)

## Configuration
Before running the Docker setup, ensure to fill in your .env file with the appropriate configurations.


## Cluster Mode
To run Redis in cluster mode, execute:
```bash
docker-compose up -d
```

## Non-Cluster Mode
To run Redis in non-cluster mode, execute:
```bash
docker-compose up -d
```

## ToDo
- [ ] add password for redis
