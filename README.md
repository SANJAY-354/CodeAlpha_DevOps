# CodeAlpha_DevOps
# DevOps Internship Tasks

This repository contains the DevOps internship tasks completed as part of my internship program. The tasks demonstrate practical knowledge of Docker, Jenkins, Gradle, Java, and CI/CD concepts.

## Repository Structure

```
DevOps-Internship/
│
├── Task-2-Jenkins-Remoting/
│
├── Task-3-Gradle-App/
│
└── Task-4-Docker-WebServer/
```

---

# Task 2 – Jenkins Master-Agent Setup

## Objective

Set up Jenkins with a remote build agent and execute a build on the connected agent.

## Tools Used

- Jenkins 2.555.3
- Java JDK 21
- Windows
- PowerShell

## Steps Performed

- Installed Jenkins.
- Configured Java 21.
- Created a Jenkins agent (agent1).
- Connected the agent using Jenkins Remoting.
- Created a Freestyle Project.
- Executed a build successfully on the remote agent.

## Output

- Jenkins agent connected successfully.
- Build executed successfully.
- Console output displayed "Finished: SUCCESS".

---

# Task 3 – Java Application Build using Gradle

## Objective

Build and manage a Java application using Gradle and automate the build process.

## Tools Used

- Java JDK 21
- Gradle
- Jenkins

## Steps Performed

- Installed Gradle.
- Configured Gradle with Java 21.
- Created a Java application using Gradle.
- Built the application using:

```
gradle build
```

- Executed the application using:

```
gradle run
```

- Integrated the project with Jenkins for automated builds.

## Output

- Gradle project created successfully.
- Build completed successfully.
- Application executed successfully.

---

# Task 4 – Docker Web Server

## Objective

Create a Docker container that hosts a simple static website using Nginx.

## Tools Used

- Docker Desktop
- Nginx
- HTML

## Project Files

```
Dockerfile
index.html
```

## Docker Commands Used

Build Image

```
docker build -t my-webserver .
```

Run Container

```
docker run -d -p 8080:80 my-webserver
```

View Running Containers

```
docker ps
```

Stop Container

```
docker stop <container-id>
```

## Output

The website was successfully hosted inside a Docker container and accessed through:

```
http://localhost:8080
```

---

# Technologies Used

- Docker
- Jenkins
- Gradle
- Java 21
- Git
- GitHub
- Windows
- PowerShell

---

# Learning Outcomes

Through these tasks, I learned:

- Docker image creation and container management.
- Jenkins installation and distributed build architecture.
- Jenkins Master-Agent communication.
- Gradle project initialization and build automation.
- Java application build process.
- Basic CI/CD workflow.
- Version control using Git and GitHub.

---

# Author

**Sanjay**

DevOps Intern
