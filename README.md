# Development environment

## Setup

```
$ docker compose up -d
```

# Production environment

## Config

- Create a copy of file **.envs/production/.postgres.dist** and rename to **.envs/production/.postgres**. Set
the desired value for postgres virtual environment variables

- Create a copy of file **compose/production/odoo/config/odoo.conf.dist** and rename to **compose/production/odoo/config/odoo.conf**. Set
the desired configuration for odoo server.

- Create the folder **compose/production/nginx/ssl** and copy inside the files cert.pem and key.pem for ssl setup.


## Setup

```
$ docker compose -f production.yml -p odoo-prod up -d
```
