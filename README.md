# DevOps Task 1 - CI/CD Pipeline Using GitHub Actions

## Objective

Automate the build and deployment process of a Node.js application using GitHub Actions and Docker.

## Technologies Used

* Node.js
* Express.js
* Docker
* GitHub
* GitHub Actions

## Project Structure

* index.js
* package.json
* Dockerfile
* .github/workflows/main.yml

## CI/CD Workflow

1. Trigger on push to main branch
2. Checkout repository
3. Setup Node.js
4. Install dependencies
5. Verify application build
6. Complete workflow

## Docker Commands Used

Build Docker Image:
docker build -t devops-task-new .

Run Docker Container:
docker run -p 3000:3000 devops-task-new

## Output

Application runs successfully and displays:

CI/CD Pipeline Working!
