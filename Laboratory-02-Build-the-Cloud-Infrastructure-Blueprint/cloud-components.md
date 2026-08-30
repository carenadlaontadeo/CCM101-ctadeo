## CLOUD INFRASTRUCTURE COMPONENTS

## 1. Compute Resources
### Purpose
Compute resources provide the processing power needed to run applications, services, and workloads. They include the CPU and memory available to a server.

### Importance in Cloud Computing
Compute resources are important because they allow cloud users to run applications without managing physical hardware directly. Cloud providers can provide different amounts of processing power depending on the needs of a workload.

### KillerCoda Environment
The KillerCoda Linux environment uses an Intel Xeon E312xx virtual CPU with 1 CPU core. The server also has approximately 1.9 GiB of RAM. The system is running in a virtualized environment using the KVM hypervisor.


## 2. Storage Resources
### Purpose
Storage resources are used to store the operating system, applications, files, and other data.

### Importance in Cloud Computing
Storage is important because cloud applications need a reliable location for storing and accessing data. Cloud storage allows organizations to store data without relying entirely on local physical devices.

### KillerCoda Environment
The KillerCoda environment uses virtual disk storage. The main file system is `/dev/vda1`, which has a capacity of 19 GB and is mounted on `/`. Other mounted file systems include `/boot` and `/boot/efi`.


## 3. Networking Resources
### Purpose
Networking resources allow communication between computers, servers, applications, and users.

### Importance in Cloud Computing
Networking is important because cloud services need to communicate with users and other services through networks. Networking also allows cloud resources to connect to the internet.

### KillerCoda Environment
The primary network interface is `enp1s0`, which has the IP address `172.30.1.2`. The environment also contains the Docker network interface `docker0`, which has the IP address `172.17.0.1`.


## 4. Operating System
### Purpose
An operating system manages the hardware and software resources of a computer. It provides an environment where applications and services can run.

### Importance in Cloud Computing
Operating systems are important because cloud servers need an operating system to manage compute, storage, networking, users, and applications.

### KillerCoda Environment
The KillerCoda server is running Ubuntu Linux with kernel version `6.8.0-138-generic`. Linux is commonly used in cloud environments because it supports server workloads and provides powerful command-line administration tools.
