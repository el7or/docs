# Technical Architecture

## System Architecture Diagram
A high-level diagram illustrating the interactions between the **front-end**, **back-end**, **database**, and **external services**. This architecture ensures seamless integration and efficient data flow between the various components of the platform.

## Frameworks and Technologies
| **Layer**       | **Technology/Framework**         | **Purpose**                              |
|-------------|-------------------------------|--------------------------------------|
| Front-End   | Angular, Google Blockly       | User Interface                      |
| Back-End    | .Net Core, ABP.IO, Node.js    | Application Logic, API Layer        |
| Desktop     | Electron JS                  | Desktop Application Interface       |
| Database    | SQL Server, MongoDB          | Data Storage and Management         |
| Cloud       | Azure, AWS, GCP              | Hosting, File Storage               |
| Security    | OAuth, JWT, Openiddict       | Authentication & Authorization      |

### Deployment Architecture
The Akadimi platform supports flexible deployment options, enabling scalability and performance optimization:
- **Modular Monolith**: A structured approach where key components are logically separated but deployed together for simplicity and efficiency.
- **Microservices** (using Kubernetes, Docker Swarm, Helm): Allows for independent deployment and scaling of services, enhancing system flexibility and resilience.
- **Micro Frontend Architecture**: Breaks down the front-end into smaller, independently deployable pieces, improving modularity and ease of maintenance.


## Security and Data Protection
- **Encryption**: Ensures that sensitive data is encrypted during transmission and storage, safeguarding user privacy and integrity.
- **Authentication**: Utilizes OAuth, JWT, and Openiddict to secure access to the platform, enabling trusted and authorized users to interact with the system.
- **Compliance**: Adheres to **GDPR** and other relevant regulations, ensuring that the platform meets global standards for data protection and user privacy.
