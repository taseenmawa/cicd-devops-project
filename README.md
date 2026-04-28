# CI/CD Pipeline Project

## What this project does
Automatically deploys a Dockerised Flask app to AWS EC2 
whenever code is pushed to GitHub.

## Tech Stack
- Python Flask
- Docker
- GitHub Actions (CI/CD)
- AWS EC2 (Ubuntu)

## Architecture
GitHub Push → GitHub Actions → Build Docker Image → Deploy to EC2 → Live App
