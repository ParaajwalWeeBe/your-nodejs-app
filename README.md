## CI/CD Pipeline with GitHub Actions

### Objective
Automate the build and deployment of a Node.js web app using GitHub Actions and Docker.

### Steps Followed
1. Created a Node.js app with Express.
2. Added a Dockerfile to containerize the app.
3. Pushed code to a GitHub repo.
4. Created `.github/workflows/main.yml` for CI/CD.
5. Configured GitHub Actions to:
   - Checkout code
   - Set up Node.js environment
   - Install dependencies
   - Build and push Docker image to DockerHub
6. Added DockerHub credentials as GitHub Secrets.
7. CI/CD pipeline runs on push to `main` branch.

### Result
Every code push to `main` triggers an automated pipeline that builds and deploys the app as a Docker image.

