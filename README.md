# BriteCore REST API Specification

<div>
  <span>
    <img src="https://img.shields.io/badge/OAS3-compliant-20b120.svg">
  </span> 
</div>

</br>

**BriteCore REST API** specification for the **API** developed in the **BriteCore Hiring Project**.

## Description

This repository contains the specification for the **BriteCore REST API** following the **OpenAPI Specification 3**   
and also provides **Swagger Editor** and **Swagger UI**.

## Directory Structure

This is the directory structure followed:

```bash
.
└── specification
└── deploy
```

#### Structure Description

1. **Specification**: This folder is the root folder for all specifications.
2. **Deploy**: This folder contains the scripts and **CloudFormation** definitions to deploy the application.


## Getting Started

The infrastructure is implemented using **Docker** and **Docker Compose**.

### **Requirements**

For **development** and **production** environments:
- [Docker](https://docs.docker.com/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Development Environment

To set up the development environment follow the steps of the guide below.

### Setting Up the Development Environment

To have the development environment running you will need **Docker** and **Docker Compose** installed.

### 1 Development Environment Initialization

Inside of **britecore-api-specs**.

1. Build the Docker containers using:

```bash
docker-compose build
```

2. Start the development environment using:

```bash
docker-compose up
```

When the command finishes the services will be running and can be accessed at:

**Swagger Editor**  
[http://localhost:8081](http://localhost:8081)  

**Swagger UI**  
[http://localhost:8082](http://localhost:8082)  

---

If you have any questions or feedback, do not hesitate to contact me  
 at andre_savioli@hotmail.com. I will be glad to help.