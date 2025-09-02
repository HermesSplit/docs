# Hermes
Hermes is a free and opensource expense splitting tool that does not require a account. It aims to split group expenses in a transparent and concise way.

## Stack
- Docker Compose
- AngularJS (Angular Universal and capacitor)
- Spring Boot
- PostgreSQL
- Github Actions
- Redis
- Grafana + Prometheus + Loki

## Architecture
The frontend (Angular Universal), backend (Spring Boot), Database(PostgreSQL) and cache(Redis) will be on separate containers. They will have separate dockerfiles and have docker will use docker compose for running these containers.
