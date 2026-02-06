# PID Controller Documentation for Node-RED in Docker

---

## 1. Introduction

- **Purpose**: This documentation outlines the setup and usage of a PID (Proportional, Integral, Derivative) controller implemented using Node-RED and running in Docker.

- **Scope**: Covers installation, configuration, and troubleshooting of the PID controller.

---

## 2. Requirements

### Software Requirements

- Node-RED
- Docker
- Optional: Node-RED dashboard nodes

---

## 3. Installation

### 3.1. Setting Up Docker

1. **Install Docker**: Follow the official guide to install Docker on your operating system.
   
2. **Verify Installation**:
   ```bash
   docker --version
   ```
### 3.2. Pull Node-RED Docker Image
   ```bash
   docker pull nodered/node-red:latest-20-minimal
   ```
---

## 4. Run Node-RED in Docker compose
   ``` bash
   docker-compose up -d
   ```
---

## 5. Accessing Node-RED

Open a web browser and navigate to http://localhost:1880
Import flows.json file and Deploy

### 5.1. Accessing Node-RED User Interface

Open a web browser and navigate to http://localhost:1880/ui

---

## 8. Conclusion

Using a PID controller in Node-RED within a Docker environment provides flexibility and ease of deployment for various automation tasks.

---

## 9. References
- [Node-RED Documentation](https://nodered.org/docs/)
- [Docker Documentation](https://docs.docker.com/)

