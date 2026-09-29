# Docker Compose Guide

## What does the `services:` block do?

The `services:` block defines the containers that will be created and managed by Docker Compose. In this deployment, it contains two services: `database` for MariaDB and `app` for Nextcloud.

## How does the Nextcloud app find the database?

The Nextcloud app uses the `MYSQL_HOST` environment variable to identify the database service. In the Compose file, it is set to `database`, which matches the name of the MariaDB service.

```yaml
- MYSQL_HOST=database
```

This allows the Nextcloud container to communicate with the MariaDB container using the service name.

## What is the difference between `docker run` and `docker-compose up -d`?

The `docker run` command is normally used to create and start an individual container using command-line options. In contrast, `docker-compose up -d` uses the configuration in the `docker-compose.yml` file to create and start multiple related containers together in the background.

## Infrastructure as Code

Docker Compose allows the deployment configuration to be written as code in a YAML file. This makes the infrastructure easier to reproduce, manage, and document.
