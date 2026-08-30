# Laboratory 02 – Build the Cloud Infrastructure Blueprint

## Mission Overview

This laboratory activity focused on investigating the infrastructure components of a cloud-based Linux server. Using the KillerCoda Playground, I examined the server environment and identified its compute, storage, networking, and operating system resources. I also compared the core infrastructure services offered by AWS, Microsoft Azure, and Google Cloud Platform and created a simple cloud infrastructure diagram.

## Objectives

- Explain the major components of cloud infrastructure.
- Investigate the hardware and software resources available in a Linux environment.
- Differentiate compute, storage, networking, and operating system resources.
- Understand the relationship between cloud infrastructure components.
- Create technical documentation using Markdown.
- Continue developing my GitHub Cloud Computing Portfolio.

## Cloud Infrastructure Components

### Compute Resources

Compute resources provide the processing power needed to run applications and services. In the KillerCoda environment, the server used an Intel Xeon E312xx virtual CPU with 1 CPU core and approximately 1.9 GiB of RAM.

### Storage Resources

Storage resources are used to store the operating system, applications, files, and other data. The KillerCoda environment used virtual disk storage, with the main `/dev/vda1` partition having a capacity of 19 GB.

### Networking Resources

Networking resources allow communication between users, servers, and cloud services. The KillerCoda environment used the `enp1s0` network interface with the IP address `172.30.1.2`.

### Operating System

The operating system manages the hardware and software resources of the server. The KillerCoda environment was running Ubuntu Linux with kernel version `6.8.0-138-generic`.

## Tools Used

- KillerCoda Playground
- Linux Terminal
- GitHub
- Draw.io
- Web Browser

## Linux Commands Executed

- `cat /etc/os-release`
- `uname -a`
- `lscpu`
- `nproc`
- `free -h`
- `df -h`
- `hostname`
- `ip addr`

These commands were used to gather information about the operating system, kernel version, CPU, memory, disk capacity, mounted file systems, hostname, and IP address.

## Skills Learned

During this laboratory activity, I learned how to investigate a Linux server using command-line tools. I also improved my understanding of cloud infrastructure components such as compute, storage, networking, and operating systems.
I also improved my skills in creating Markdown documentation, organizing files in GitHub, and designing a simple cloud infrastructure diagram.

## Challenges Encountered

One challenge I encountered was understanding the different Linux commands and identifying which information was required for the infrastructure report. I also needed to understand the relationship between compute, storage, networking, and operating system resources.
Another challenge was organizing the documentation and screenshots correctly in the GitHub repository. However, by completing each checkpoint step by step, I was able to better understand the purpose of each task and organize the laboratory activity properly.
