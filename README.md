# Project Title

## Description
This project is a web application built with Node.js and Next.js.

## CI/CD Pipeline

This project uses GitHub Actions for Continuous Integration and Continuous Deployment (CI/CD). The pipeline is defined in the `.github/workflows/ci.yml` file.

### How to Use the CI/CD Pipeline

1. **Push Changes**: Any changes pushed to the `main` branch will trigger the CI/CD pipeline.
2. **Build Process**: The pipeline will build Docker images for both the backend and frontend services.
3. **Testing**: You can add your test commands in the `Run tests` step of the CI workflow.
4. **Deployment**: Modify the workflow file to include deployment steps if needed.

### Local Development

To run the application locally, use the following commands:

```bash
docker-compose up
```

This will start the backend, frontend, and MongoDB services.
