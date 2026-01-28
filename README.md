# GitHub Pages CI/CD Deployment Workflow

This project demonstrates a simple Continuous Integration and Continuous Deployment (CI/CD) pipeline using **GitHub Actions** to deploy a static website to **GitHub Pages**.

## Project Overview
The workflow automatically deploys a static `index.html` page whenever changes are pushed to the `main` branch **and only when the `index.html` file is modified**.

## Technologies Used
- GitHub Actions
- GitHub Pages
- HTML

## How It Works
- A push to the `main` branch triggers the workflow
- The workflow runs **only if `index.html` is changed**
- GitHub Actions builds and deploys the site to GitHub Pages

## Live Website
https://dannydma.github.io/CI-CD-deployment-workflow/

## Workflow File
The deployment logic is defined in:

https://roadmap.sh/projects/github-actions-deployment-workflow