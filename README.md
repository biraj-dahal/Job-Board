# Job Board Application Overview

This project is a Job Board Application where:

- Companies can create accounts and post job listings with descriptions, required skills, and salary ranges.
- Job seekers can search for jobs by categories, location, and keywords, create accounts, and apply for jobs by uploading resumes.
- Admins can manage job postings, review applications, and approve or reject companies and job listings.

## Tech Stack

### Frontend:
- **Angular**: For building the user interface (UI) for job search, application forms, and admin dashboard.

### Backend:
- **NestJS**: For creating the REST API and GraphQL-based services to manage job postings, applications, and user accounts.
- **GraphQL**: To provide a flexible query interface between the frontend and backend.

### Database:
- **PostgreSQL**: To store job listings, user information, applications, and more.

### Containerization:
- **Docker**: For containerizing the application and making it easy to deploy.

### Orchestration:
- **Kubernetes**: For managing containers, load balancing, and scaling.

## Project Structure

| **Directory/File**          | **Description**                             |
|-----------------------------|---------------------------------------------|
| **backend/**                | Contains backend-related files              |
| ├── **Dockerfile**          | Dockerfile for the backend                  |
| ├── **nestjs-app/**         | NestJS backend code                         |
| **frontend/**               | Contains frontend-related files             |
| ├── **Dockerfile**          | Dockerfile for the frontend                 |
| ├── **angular-app/**        | Angular frontend code                       |
| **database/**               | Contains database-related files             |
| ├── **docker-compose.yml**  | Docker Compose configuration                |
| ├── **init.sql**            | SQL to initialize the database              |
| **kubernetes/**             | Contains Kubernetes deployment files        |
| ├── **backend-deployment.yml** | Kubernetes deployment for backend        |
| ├── **frontend-deployment.yml**| Kubernetes deployment for frontend       |
| ├── **postgres-deployment.yml**| Kubernetes deployment for PostgreSQL     |


