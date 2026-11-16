# Docker Image Management

## Introduction

Docker image management involves creating, managing, and distributing Docker images. Docker images are the building blocks of Docker containers, which are lightweight and portable virtualized environments that can run anywhere. It uses a layered architecture to build and manage Docker images. Each layer in the Docker image represents a specific set of changes or additions to the previous layer.

## Docker Image Archive

Docker provides two different methods to save and load Docker images:

* docker save/docker load


**docker save** and **docker load** are used to save and load entire Docker images along with all of their layers and metadata.


* docker export/docker import


**docker export** and **docker import** are used to export and import a container as a tar file. Docker export and docker import do not include metadata or information about the image's layers.

