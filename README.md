# Docker Compose Collection

This repository contains ready-to-use Docker Compose files for various services. The goal is to allow users to install and run services with a single command.

## How to Use

To run any service, follow these steps:

1.  Navigate to the service directory:
    ```bash
    cd <service-folder-name>
    ```
2.  Start the service using Docker Compose:
    ```bash
    docker compose up -d
    ```

## Available Services

- **MongoDB** (`mongodb/`)
- **MySQL** (`mysql/`)
- **PostgreSQL** (`postgres/`)
- **Redis** (`redis/`)
- **Weaviate** (`weaviate/`)

More services will be added in the future.
