# docker-
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


