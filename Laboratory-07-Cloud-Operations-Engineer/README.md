# Laboratory 07: The Cloud Operations Engineer

## Mission Overview
This laboratory focuses on monitoring Linux system resources and observing a running Nginx container using Docker commands.

## Objectives
- Check the system's memory and disk capacity.
- Deploy an Nginx container and simulate HTTP requests.
- Examine container logs and identify a 404 error.
- Monitor container CPU and memory usage.

## Monitoring Commands Executed
- `free -h` — checks memory usage.
- `df -h /` — checks root disk capacity.
- `top` — monitors running system processes.
- `docker run -d --name client-website -p 8080:80 nginx` — deploys the Nginx container.
- `curl http://localhost:8080` — tests the website.
- `curl http://localhost:8080/hidden-admin-page` — tests a nonexistent page.
- `docker logs client-website` — views container logs.
- `docker stats` — monitors container resource usage.

## Skills Learned
I learned how to check Linux system resources, deploy and test an Nginx container, identify HTTP errors through logs, and monitor container CPU and memory usage using Docker.
