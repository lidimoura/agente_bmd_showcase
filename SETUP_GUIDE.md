# Setup Guide for Agente BMD Showcase

## Introduction
This guide provides comprehensive instructions on how to set up and deploy the Agente BMD Showcase template.

## Prerequisites
Before you begin, ensure you have the following installed:
- Node.js (v14.x or later)
- npm (Node Package Manager)
- Git
- An IDE or text editor of your choice (e.g., VSCode, Atom)

## Step 1: Clone the Repository
First, you need to clone the repository to your local machine. Open a terminal and run:

```bash
git clone https://github.com/lidimoura/agente_bmd_showcase.git
```

## Step 2: Navigate to the Project Directory
Change to the project directory:

```bash
cd agente_bmd_showcase
```

## Step 3: Install Dependencies
Once you are in the project directory, install the necessary dependencies:

```bash
npm install
```

## Step 4: Configure Environment Variables
Create a `.env` file in the root directory of the project and add the required environment variables. You can refer to the `.env.example` file for guidance.

## Step 5: Build the Project
Before deploying, you need to build the project. Run the following command:

```bash
npm run build
```

## Step 6: Deploying the Application
Depending on your hosting solution, the deployment steps may vary. Here are common options:
### Option 1: Deploy on Vercel
1. Sign in to your Vercel account.
2. Click on `New Project`.
3. Import your GitHub repository.
4. Follow the on-screen instructions to deploy.

### Option 2: Deploy on Heroku
1. Sign in to your Heroku account.
2. Create a new app.
3. Connect your GitHub repository.
4. Enable automatic deployments or manually deploy:
   - Push the built code to the Heroku Git remote.

## Additional Resources
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [npm Documentation](https://docs.npmjs.com/)
- [Vercel Documentation](https://vercel.com/docs)
- [Heroku Documentation](https://devcenter.heroku.com/categories/reference)

## Troubleshooting
If you encounter issues during setup or deployment, refer to the FAQs or seek help from the community.

## Conclusion
Following these steps will help you set up and deploy the Agente BMD Showcase template successfully. If you have questions, feel free to reach out!
