# Docker Interview Notes

## What is Docker?

Docker is a containerization platform used to package an application along with its dependencies into a container. These containers run consistently across different environments like local machines, servers, or cloud. They are lightweight because they share the host OS, so they start fast and are efficient. This helps in faster development and deployment in DevOps.

---

## What is Image?

Docker image is a blueprint that contains the application along with its dependencies and configuration. It is used to create containers. Images are lightweight and portable, so they can run anywhere and ensure consistency.

---

## What is Container?

Docker container is a running instance of a Docker image. It contains the application along with its dependencies and runs in an isolated environment. Containers are lightweight because they share the host operating system, so they start quickly and use fewer resources. They ensure that the application runs consistently across different environments.

---

## What is Docker Hub?

Docker Hub is a cloud-based repository where we can store, manage, and share Docker images. It allows developers to pull existing images and push their own images for reuse. It helps in collaboration and makes deployment easier. It is widely used as a central registry in Docker workflows.

---

## Image vs Container (Best 5 Points)

### 1. Definition  
“Image is a blueprint or template, while container is a running instance of that image.”

### 2. State  
“Image is static and read-only, whereas container is dynamic and changes during execution.”

### 3. Purpose  
“Image is used to create containers, and container is used to run the actual application.”

### 4. Storage vs Execution  
“Image is stored in a registry or locally, while container is executed on the system.”

### 5. Number / Usage  
“One image can create multiple containers, but each container runs as a separate instance.”

### Closing  
“So image defines what to run, and container is the actual running application.”

---

## Advantages of Docker

### 1. Consistency across environments  
“Docker ensures the application runs the same on local, server, or cloud, eliminating environment-related issues.”

### 2. Lightweight and fast  
“Containers are lightweight because they share the host OS, so they start quickly and use fewer resources.”

### 3. Easy deployment  
“Applications can be packaged into containers and deployed easily, which speeds up development and release cycles.”

### 4. Isolation  
“Each container runs in an isolated environment, so one application does not affect another.”

### 5. Scalability  
“Docker makes it easy to scale applications by running multiple containers as needed.”

### Closing  
“So Docker improves consistency, speed, and scalability, making it very useful in DevOps workflows.”

---

## Virtualisation vs Containerisation

### One-line difference  
“Virtualisation creates full virtual machines, while containerisation runs applications in isolated environments on the same OS.”

### 1. Level  
“Virtualisation works at the hardware level using a hypervisor, while containerisation works at the application level.”

### 2. Operating System  
“In virtualisation, each VM has its own full OS, whereas in containerisation all containers share the host OS.”

### 3. Performance & Speed  
“VMs are slower because they require a full OS to boot, while containers are fast since they run directly on the host OS.”

### 4. Size & Resource Usage  
“VMs are heavy (in GBs), while containers are lightweight (in MBs) and use fewer resources.”

### 5. Isolation  
“VMs provide strong isolation with separate OS, while containers provide process-level isolation.”

### Closing  
“So virtualisation is more heavy and secure, while containerisation is lightweight, faster, and widely used in modern DevOps.”