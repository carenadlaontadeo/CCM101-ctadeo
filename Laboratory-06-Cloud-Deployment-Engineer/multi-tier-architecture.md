# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A Two-Tier Architecture is a system divided into two main layers: the Web/Application Tier and the Database Tier. In this activity, the Nextcloud application serves as the web/application tier, while MariaDB serves as the database tier.

## The Web/Application Tier

The Web/Application Tier is responsible for providing the user interface and handling HTTP requests from users. In this deployment, the Nextcloud container provides the web interface that users access through a browser.

## The Database Tier

The Database Tier is responsible for storing persistent information needed by the application. In this deployment, the MariaDB container stores the database information used by Nextcloud, including user accounts and file metadata.

## Why Separate Them?

Separating the web server and database into two containers makes the system easier to manage and maintain. Each container has a specific responsibility, and changes or problems in one tier can be handled separately from the other.
