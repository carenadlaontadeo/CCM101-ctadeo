# Mission 4: The Cloud-Native Engineer

## Mission Overview

Congratulations! After successfully guiding our clients through multi-cloud evaluations, you have been promoted to the Cloud-Native Engineering Team at CloudNova Technologies.

Modern cloud computing is no longer just about renting Virtual Machines (VMs) from AWS or Azure. Today's enterprise applications are built using lightweight, portable, and lightning-fast technologies called Containers.

Your new mission is to understand the shift from traditional virtualization to containerization.

Using the KillerCoda Playground, you will step into the shoes of a Cloud-Native Engineer. You will research the differences between VMs and containers, execute your very first Docker commands, and deploy a live, containerized web server in seconds.

Remember: A traditional system administrator manages servers, but a cloud-native engineer manages the services running on them.

## Objectives

At the end of this laboratory activity, you should be able to:

- Differentiate between traditional Virtual Machines (VMs) and Containers.
- Access a Docker-enabled cloud environment using KillerCoda.
- Execute fundamental Docker CLI (Command Line Interface) commands.
- Pull, run, manage, and terminate a containerized application (Nginx).
- Create professional technical documentation of container operations using Markdown.
- Continue developing a well-organized GitHub Cloud Computing Portfolio.

## Docker Commands Executed

### Checkpoint 3 - Docker Verification

```bash
docker --version
```

```bash
sudo systemctl status docker
```

### Checkpoint 4 - Nginx Deployment

```bash
docker pull nginx
```

```bash
docker run -d --name nginx-server -p 8080:80 nginx
```

```bash
curl http://localhost:8080
```

### Checkpoint 5 - Container Lifecycle

```bash
docker ps
```

```bash
docker stop nginx-server
```

```bash
docker ps -a
```

```bash
docker rm nginx-server
```

## Skills Learned

Through this activity, I learned how to use Docker in a Linux environment through the KillerCoda Playground. I learned how to pull and run an Nginx image, map a port, verify a running web server, and manage the lifecycle of a container. I also practiced documenting technical procedures using Markdown and organizing my Cloud Computing Portfolio in GitHub.

## Challenges Encountered

One challenge I encountered was understanding the different Docker commands and what each command does. I also had to make sure that the Nginx container was running correctly and that the port mapping was working when I tested it using curl. Another challenge was organizing the required Markdown files and screenshots in the correct GitHub folders. Following the checkpoints one at a time helped me complete the activity and understand the Docker container lifecycle.
