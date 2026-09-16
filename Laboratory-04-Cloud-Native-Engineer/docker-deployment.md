# Docker Deployment

## Checkpoint 5 - The Container Lifecycle

### 1. List Running Containers

```bash
docker ps
```

This command lists the containers that are currently running.

### 2. Stop the Running Container

```bash
docker stop nginx-server
```

This command stops the running Nginx container named `nginx-server`.

### 3. Verify It Is Stopped

```bash
docker ps -a
```

This command displays all containers and verifies that the `nginx-server` container has stopped.

### 4. Remove the Container Completely

```bash
docker rm nginx-server
```

This command removes the stopped `nginx-server` container completely.
