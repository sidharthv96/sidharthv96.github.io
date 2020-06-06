Helios-Webhooks

- Service which facilitates to Integrate Webhooks functionality to any internal product
- Supports [CloudEvent](https://cloudevents.io/) spec
- Kubernetes Microservices (Java & Node.js), Kafka, Vault, CI/CD (Gitlab, Jenkins & Helm)
- Multiple endpoint autentication type support
- Atleast once delivery, Automatic Retries with exponential backoff
- Endpoint blacklisting and optional Deadletter requeuing
- Message expiry support

Helios-Extensions

- Allow customer to write custom code to act on system events.
- Uses Webhooks and Serverless Platform (Oracle Fn)
- Designed the mutli tenancy architecture which allows managint and running customer functions securely
- Created a federated Docker registry poxy service which allows cutomers to push containers with 0-config while managing access control and tenant data segeregation.

Vision

- Created a Typescript library to provide core functionality required to build a Microservice with Node.js
- Kafka - Avro schemas | Transparent message encryption with Vault
- HTTP endpoints - Express | Swagger
- Service AuthN/AuthZ - JWT | Vault
- Metrics & Health checks - Prometheus
- Easy structured logging - Pino
- Dependency Injection - Inversify
- Comprehensive test coverage and test helpers - Jest

CX-Hyperconnect Hackathon Management System

- Participant Registration, Team Formations, Idea Wall
- Multiple Judgement Panels with Different Point systems, Non-Colliding Time slots for Teams, Volunteer Co-ordination Reports
- Promotional Games to drive engagement
- Built with Oracle APEX

Element Manager

- Product that supports Import/Export of Custom Elements like Reports, Workspaces, etc in Oracle Service Cloud
- Redesigned the UI to improve UX
- Created a Generic Framework to standardise Metadata management for multiple types of objects.
- Developed a Jenkins Pipeline to automate exports and imports for different sites using Element Manager Public API
