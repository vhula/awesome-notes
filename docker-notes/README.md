# [Up](../README.md)

# Docker notes

## Contents

  * [Overview](#overview)
  * [Docker terminology](#docker-terminology)
  * [Resources](#resources)
  * [Links](#links)
  
## Overview

Docker is not a VM.

Docker uses Linux containers ([LXC](https://en.wikipedia.org/wiki/LXC)).

## Docker terminology

**Docker Image** - The representation of a Docker Container. It's a template
(snapshot) of a container.

**Docker Container** - A container image is a lightweight, stand-alone, 
executable package of a piece of software that includes everything needed to 
run it: code, runtime, system tools, system libraries, settings. Available for 
both Linux and Windows based apps, containerized software will always run the 
same, regardless of the environment. Containers isolate software from its 
surroundings, for example differences between development and staging 
environments and help reduce conflicts between teams running different 
software on the same infrastructure. [[1]](https://www.docker.com/what-container)

**Docker Engine** - The code which manages Docker stuff. Creates and runs Docker
Containers.

## Resources

[Docker Documentation](https://docs.docker.com)

[Docker Hub](https://hub.docker.com)

## Links
1. [What is a Container](https://www.docker.com/what-container)