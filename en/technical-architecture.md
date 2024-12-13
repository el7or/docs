# Technical Architecture

## System Architecture Diagram
A high-level diagram illustrating interactions between front-end, back-end, database, and external services.

## Frameworks and Technologies
| **Layer**       | **Technology/Framework**         | **Purpose**                              |
|-------------|-------------------------------|--------------------------------------|
| Front-End   | Angular, Google Blockly       | User Interface                      |
| Back-End    | .Net Core, ABP.IO, Node.js    | Application Logic, API Layer        |
| Desktop     | Electron JS                  | Desktop Application Interface       |
| Database    | SQL Server, MongoDB          | Data Storage and Management         |
| Cloud       | Azure, AWS, GCP              | Hosting, File Storage               |
| Security    | OAuth, JWT, Openiddict       | Authentication & Authorization      |

### Deployment Patterns
- Modular Monolith
- Microservices (using Kubernetes, Docker Swarm, Helm)
- Micro Frontend Architecture

## Security and Data Protection
- **Encryption**: Ensures sensitive data is encrypted during transmission and storage.
- **Authentication**: OAuth, JWT, Openiddict for secure access.
- **Compliance**: Adheres to GDPR and other regulations.
