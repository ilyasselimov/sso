# Golang SSO (Single Sign-On) Service

This repository contains the source code of a Single Sign-On (SSO) authentication service implemented in Go.  
The project was developed as a step-by-step guide, covering the entire process of building a modern gRPC-based backend service from scratch.

---

## What this project demonstrates

- Designing and implementing a **protobuf contract** with gRPC
- Project scaffolding and clean architecture structure
- Application configuration and structured logging
- Configuration management using **YAML** files  
- User authentication and authorization:
  - Registration and login handlers
  - Password hashing and verification
  - JWT access/refresh tokens
  - Role checks 
- Database migrations (SQLite)
- Automation of common tasks with **Taskfile**
- Data persistence and storage layer implementation
- Functional and integration tests
- Integration with another microservice (URL Shortener)
- Deployment to a cloud server and validation of the running service
- Graceful shutdown and proper resource management

---
### Example Service Startup and Logging Output

The following is a sample console output showing the SSO service startup process.  
The logs demonstrate:

- Initialization of the service with the environment set to `local`  
- Loading of the configuration, including server port, timeouts, and storage path  
- Structured output of configuration details  
- Examples of log messages at various levels: INFO, DEBUG, ERROR, and WARN

To enhance the readability of logs during development, this project uses a custom logging handler based on Go's `slog` package combined with the [`fatih/color`](https://github.com/fatih/color) library for colored output.

The custom handler (`slogpretty.PrettyHandler`) outputs logs in a pretty JSON-like format with color highlighting for different log levels:

<img width="843" height="800" alt="image" src="https://github.com/user-attachments/assets/297c7e0a-7feb-4c09-9534-339748957aab" />



This project uses the module https://github.com/ilyasselimov/protos 

