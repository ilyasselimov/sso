# Golang SSO (Single Sign-On) Service

This repository contains the source code of a Single Sign-On (SSO) authentication service implemented in Go.  
The project was developed as a step-by-step guide, covering the entire process of building a modern gRPC-based backend service from scratch.

---

## What this project demonstrates

- Designing and implementing a **protobuf contract** with gRPC
- Project scaffolding and clean architecture structure
- Application configuration and structured logging
- User authentication and authorization:
  - Registration and login handlers
  - Password hashing and verification
  - JWT access/refresh tokens
  - Role checks 
- Database migrations (SQLite)
- Data persistence and storage layer implementation
- Functional and integration tests
- Integration with another microservice (URL Shortener)
- Deployment to a cloud server and validation of the running service
- Graceful shutdown and proper resource management

---

This project uses the module https://github.com/ilyasselimov/protos 

