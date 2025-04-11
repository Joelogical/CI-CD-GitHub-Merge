# CI/CD GitHub Actions Implementation

## Project Overview 📋

In this project, I implemented a CI/CD pipeline using GitHub Actions to automate testing and deployment. The application:

- Runs Cypress tests automatically when changes are proposed
- Deploys to Render automatically when approved changes reach main branch
- Uses MongoDB for data storage

## What I Built 🛠️

1. **Automated Testing Pipeline**

   - Set up GitHub Actions to run when PRs are made to develop branch
   - Configured Cypress component tests
   - Added branch protection rules

2. **Automated Deployment Pipeline**
   - Connected GitHub Actions to Render
   - Set up deployment hooks
   - Configured automatic deployment on main branch updates

## Branch Structure 🌳

- `main`: Production code, automatically deploys to Render
- `develop`: Testing environment, runs Cypress tests
- Feature branches: Where I make new changes

## Technical Implementation 💻

- Created two GitHub Actions workflows:
  1. `cypress-tests.yml` for testing
  2. `render-deploy.yml` for deployment
- Set up MongoDB Atlas database
- Configured Render web service
- Implemented branch protection rules

## Live Demo 🚀

- Deployed App: https://github.com/Joelogical/CI-CD-GitHub-Merge.git
- GitHub Repo: [Repository URL]

## Technologies Used ⚙️

- GitHub Actions
- Cypress
- Render
- MongoDB Atlas
- Node.js/Express
- React

## Key Features ✨

- Automated component testing
- Continuous deployment
- Database integration
- Branch protection
- Pull request workflows

## Learning Outcomes 📚

Through this project, I learned:

- CI/CD pipeline implementation
- GitHub Actions configuration
- Branch protection strategies
- Automated testing practices
- Deployment automation

- Despite not having being able to acomplish the redner, I gave my best efforts towards the assignment. 
I will continue to examine these principles in the future.
