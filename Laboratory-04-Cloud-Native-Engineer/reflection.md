# Reflection

This laboratory activity helped me understand the difference between traditional Virtual Machines and containers. One of the first things I noticed is that setting up Docker is much simpler and faster compared to installing a complete operating system inside a virtual machine. A virtual machine needs its own guest operating system, while containers can share the host operating system. Because of this, containers can be more lightweight and faster to start.

The port mapping `-p 8080:80` was important when I deployed the Nginx container. The first number, `8080`, is the port on the host machine, while `80` is the port used by Nginx inside the container. This allowed me to access the Nginx web server through `http://localhost:8080` from the host environment.

When I used `docker rm nginx-server`, the Nginx container was completely removed. Any data stored only in the container's writable layer would also be removed. This showed me that containers are meant to be replaceable, so important data should be stored separately when it needs to be preserved.

Containerization can have a major impact on DevOps because applications can be packaged with their dependencies and deployed in a more consistent environment. Docker also makes it easier to create, run, stop, and remove application environments using simple commands.

My GitHub Cloud Computing Portfolio is also improving because I am documenting each laboratory activity in an organized way. In this activity, I added Markdown documentation, Docker commands, screenshots, and a reflection. This makes my repository a record of the cloud computing skills and practical activities I have learned throughout the semester.
