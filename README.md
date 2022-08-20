# docker- ....
Docker Tutorial
What is Docker?
Docker is an open-source container technology can be used to automate the deployment process which packages, deploys, and runs applications in any environment.

Origin of Docker
Docker, Inc. is an American technology company that develops Docker Hub and Docker Desktop. The company was founded as dotCloud, Inc. in 2010 by Solomon Hykes. Docker, Inc. started its life as platform ad a service (PaaS) provide called dotCloud. Behind the scenes, the dotCloud platform leveraged Linux contained. To help them create and manage these containers they built an internal tool that they called it as "Docker." And that's how Docker was born!

What is container?
Container is an operating system (OS) virtualization based on Linux namespaces and cgroups.  Containers don not need a separate operating system, applications inside containers dependent on host operating system. But, process, files, libraries and configurations contained inside containers are isolated from other process that runs in operating system. Every container has its own process stack, its own IP address.

Before container technologies, deploying an application usually took quite a long time. The deployment had to be done manually, which cost the company time and resources. Sometimes deployment team was quite bigger to manage the deployments in multiple environments. With the help of container technologies the deployment whole process became more streamlined and standardized. The container technologies can be used to automate the deployment process quite effortlessly and therefore the value of a well configured container platform is intangible. Docker is a tool to create an image of an application and the dependencies needed to run it. The image can then later be used on a containerization platform such as Kubernetes.
Why Docker?
If application needs to host on 10 different webservers, it needs ten physical servers under load balancing server serving the web traffic. To install servers, first it needs the hardware setup, OS installation setup then server has to be installed. This overall infrastructure is very expensive and costs to the company. Also more time is needed to setup the infrastructure.

One solution for this is running multiple virtual machines on one single physical server. But still it takes more time to setup those many virtual machines. And it is error prone as it may be hard to maintain the same environment setup and configurations in all VMs.

Containers overcome the problems we had in virtualization through VMs. We need to create an image of an application and the dependencies needed to run it. The image can then later be run in any number of containers and in any platforms. This reduces the overall time. With containers, all the possible mismatches between different software versions and operating systems are canceled out. It enables the developers to use whichever programming language and software tool they want to, if they can run it without problems inside the container. This combined with the deployment process, makes the whole ordeal agile, highly scalable and most importantly, fast.

The field of Development and Operations (DevOps) benefit greatly from containerization in the form of automating the deployment. Compared to normal virtual machines, containerized platforms require fewer configurations and can be deployed quickly with the CI/CD.
Dockerfile
A Dockerfile has all the instructions on how to build the final image for deployment and distribution.

Dockerimage
Dockerimage is the immutable snapshot of the software with its runtime environment. This can be run in container at any time later.

Virtual Machines vs Containers
virtual-machines-vs-containers-0
Virtual Machines

Containers

Virtual Machine is a Hardware virtualization.

Container is an operating system (OS) virtualization.

Virtual machines needs full operating system and all included software that come with them.

Containers are built to contain only the necessary libraries and dependencies inside them.

Deployment takes significantly more time.

Deployment takes only few seconds.

When it is needed host application in new server, deployment to virtual machine takes more time as it needs time to setup the virtual machine and all necessary software. Virtual machines are more bulky and slow to set up and configure.

Compared to virtual machines, containers are reproducible standardized environments that follow a certain ideology, create once – use many. After a container environment with the Dockerfile is manually crafted, it is available to be utilized when needed.

More cost. It needs to invest on operating system and all necessary softwares.

Cheaper and very less or no cost.  Docker is an open-source container.

Virtual machines take several gigabytes of storage space. Each virtual machine instance contains a full copy of an operating system and all the dependencies needed to run

Containers are typically only megabytes in size.

Virtual machines take several minutes to boot up.....

Dockers boot up virtually instantly.
How to install docker on Windows
In this tutorial you will learn to install docker in windows OS. Installation is easy as installing any other software by pressing Next button in multiple steps. Although we have provided the steps to install and setup docker, follow the below steps:

Step 1  
Download docker installable software from https://download.docker.com/win/stable/Docker%20Desktop%20Installer.exe

Step 2
Once the Docker Desktop Installer.exe file is downloaded, double click on exe file. The following window opens on the screen, Select both the options (Enable Hyper-V Windows Features, Add shortcut to desktop), the click Ok.

It takes several minutes to complete the installation. Once installation is complete, it ask to restart Windows. Please restart your system to complete the installation.
Step 3
Verify the docker installation. After the successful installation, docker shortcut icon will appear on the screen
From system tray verify the docker running status
To verify that the docker is successfully installed, execute the below command from command prompt, enter the command and press enter key.

docker --version
