🚀 Microservices Project with Docker and Kubernetes 🐳

This is my microservices small project in which I made everything from scratch including event bus, just for practice.

🔧 Technologies Used:
- Docker: Containerization for seamless deployment and isolation
- Kubernetes: Orchestrating and managing containerized applications
- Node.js: Backend services and APIs
- React.js: Frontend user interface

📁 Project Structure:
- `client/`: Frontend React application
- `posts/`: Microservice for creating and managing blog posts
- `comments/`: Microservice for handling post comments
- `event-bus/`: Microservice responsible for event communication
- `query/`: Microservice for querying data from multiple services
- `moderation/`: Microservice for comment moderation
- `infra/`: Kubernetes configurations and manifests

🚀 How to Use:
1. Clone the repository: `git clone https://github.com/yourusername/microservices-project.git`
2. Navigate to the project directory: `cd microservices-project`
3. Deploy the project using Skaffold: `skaffold dev`
