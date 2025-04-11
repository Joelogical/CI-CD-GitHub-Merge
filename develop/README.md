# CI/CD GitHub Actions Project

## What is this project about? 🤔
This project teaches us how to set up automated testing and deployment for our code using GitHub Actions. Think of it like having a robot that:
1. Tests our code automatically when we want to make changes
2. Deploys our website automatically when we approve those changes

## How it works 🔄
We have two main branches:
- `develop` (where we test our changes)
- `main` (where our live website code lives)

When we want to make changes:
1. Create a new feature branch from `develop`
2. Make our changes
3. Create a Pull Request to `develop`
   - GitHub Actions runs our tests automatically
   - If tests pass, we can merge our changes
4. When ready for production, merge `develop` to `main`
   - GitHub Actions automatically deploys to Render

## Technologies Used 🛠️
- GitHub Actions for automation
- Cypress for testing
- Render for deployment
- MongoDB for database

## Setup Steps 📝
1. Clone the repository
2. Create `develop` branch
3. Set up Render deployment
4. Configure GitHub Actions
5. Start making changes!

## Important Notes 📌
- Always create feature branches from `develop`
- Never push directly to `main`
- Make sure tests pass before merging
- Keep your MongoDB connection string secure

## Links 🔗
- Deployed Application: [Your Render URL]
- GitHub Repository: [Your GitHub URL]

## Need Help? 🆘
If you're stuck:
1. Check if your branches are set up correctly
2. Verify your GitHub Actions workflow files
3. Make sure your Render deploy hook is configured
4. Double-check your MongoDB connection

Happy coding! 🚀 