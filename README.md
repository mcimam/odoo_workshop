# Odoo workshop

This repo contains odoo scafold for odoo workshop.

## Installation
1. Update workshop_1 wherever you want
2. Kick start docker by using this command
``` sh
docker compose up
```
3. Modify existing container by using docker exec
``` sh
docker compose exec odoo bash
```
4. Look up DB container by using docker exec
``` sh
docker compose exec db psql -U odoo postgres
```