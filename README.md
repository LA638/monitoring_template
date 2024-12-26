## Docker compose template
For monitoring your cloud providers' billing accounts and services with Prometheus + Telegraf + Alertmanager + Grafana stack
### Create .env file
```
NSTANCE_NAME=mon.company.name
ADMIN_USER=admin
ADMIN_PASSWORD=password
```
### Run
```
docker compose up -d
```