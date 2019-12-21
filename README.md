# Docker

![it works on my machine](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRIQid16aRVh-aRN_Y9qadnpXuAtvmGEZvE1Azy8BdT4IIEHm6K&s)

`it works on my machine` if you've ever heard this excuse, Docker is a must. Docker bundles your app together with all the libraries and services it depends on into a package called a container then delivers it as a single unit. no matter what your stack or architecture looks like. you can deploy it anywhere without worrying about its components.

You don't have to worry about how you should build your app every time it changes. Docker standardizes the process through a simple configuration file. it allows you to quickly and easily run your app on Windows, Mac, or Linux hosts.

> WE PREFER WORKING SOFTWARE OVER COMPREHENSIVE DOCUMENTATION

## Prerequisites
You should have basic terminal knowledge 

# Installing Docker 
## [windows](https://docs.docker.com/docker-for-windows/install/)
Microsoft's OS features for Docker don't work in older versions, and "Windows 10 Home" edition doesn't have Hyper-V, so you'll need to install [the Docker Toolbox](https://docs.docker.com/toolbox/overview/), which is a slightly different approach to using Docker with a VirtualBox VM. This means Docker will be running in a Virtual Machine that sits behind the IP of your OS, and uses NAT to access the internet.

> NOTE FOR TOOLBOX USERS: For all examples that use http://localhost , you'll need to replace with http://192.168.99.100

## [Mac](https://docs.docker.com/docker-for-mac/install/)
 If you're on an older Mac with less than OSX Yosemite 10.10.3, you'll need to install [the Docker Toolbox](https://docs.docker.com/toolbox/overview/) instead.

## [Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
Don't use your built-in default packages like apt/yum install docker.io because those packages are old and not the Official Docker-Built packages. instead use the Docker's automated script to add their repository and install all dependencies: `curl -sSL https://get.docker.com/ | sh` 

## What if None Of These Options Work?
Maybe you don't have local admin, or your machine doesn't have enough resources!. The best free option here is to use [play-with-docker.com](https://labs.play-with-docker.com/), which will run one or more Docker instances inside your browser, and give you a terminal to play with. 

# Terms

* Dockerfile 

it define how an app should be built/packaged and deployed with Docker. They are text files with a number of commands defined in the Docker documentation

# Resources 

* [Docker’s own description](https://www.docker.com/why-docker)

* [Dockerfile documentation](https://docs.docker.com/engine/reference/builder/)

* [DevOps Road Map](https://dzone.com/articles/the-devops-roadmap-for-programmers)

* [containers are not lightweight vms](https://www.linuxfoundation.org/blog/2017/05/containers-are-not-lightweight-vms/)
