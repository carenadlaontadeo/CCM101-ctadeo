# Mission 6 Reflection

Writing a `docker-compose.yml` file makes a cloud engineer's job easier because it allows multiple containers and their configurations to be defined in one file. Instead of manually typing many commands for each container, Docker Compose can deploy the services together using one command. This makes the deployment process more organized, repeatable, and easier to manage.

YAML indentation is very important because YAML uses spaces to show the structure and relationship between different sections. If an indentation error is made, such as using a Tab instead of spaces, Docker Compose may not be able to read the configuration correctly. This can result in an error when trying to deploy the application. Therefore, the indentation must be checked carefully when creating a Compose file.

We used environment variables such as `MYSQL_PASSWORD` to provide configuration values needed by the containers. These variables allow the Nextcloud application to connect to the MariaDB database using the required database credentials and settings. They also keep the configuration organized inside the Compose file.

Deploying Nextcloud in only a few minutes showed me how useful containerization and Docker Compose can be. Seeing the Nextcloud setup page after starting both the application and database containers made the deployment process easier to understand.

Since Mission 1, my understanding of Cloud Computing has evolved from learning basic cloud concepts to actually working with cloud environments, containers, and deployment tools. I have learned that cloud computing involves not only using online services but also understanding how applications, storage, databases, containers, and infrastructure work together. This mission helped me understand the value of Infrastructure as Code and how Docker Compose can simplify the deployment of multi-container applications.
