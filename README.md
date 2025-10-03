
# 🚀 My React Static Web App on Azure

This is a simple React application deployed on **Azure Static Web Apps** using **GitHub Actions** for continuous deployment.

🌐 **Live URL:** https://calm-water-061bd4403.z01.azurefd.net

## 📁 Project Structure

myapp/
├── public/
├── src/
├── package.json
├── README.md
└── azure-static-web-apps-calm-water-061bd4403.yml

## ⚙️ Prerequisites

- Node.js (LTS version recommended)
- npm or yarn
- A GitHub account
- An Azure account with Static Web Apps enabled

## 🧱 Local Development

To run the app locally:

npm install
npm start
The app will be available at http://localhost:3001.

🌐 Deployment (CI/CD)
This project uses GitHub Actions for automatic deployments to Azure.

Each time you push to the main branch, the workflow:

Installs dependencies

Builds the app using npm run build

Deploys the build output to Azure Static Web Apps

The workflow file was generated automatically when the app was deployed from the Azure Portal:
.github/workflows/azure-static-web-apps-calm-water-061bd4403.yml

🚦 GitHub Workflow Trigger
✅ On push to main → automatic deployment to Azure

✅ On pull requests to main → preview environments are created

🧪 Useful Commands

# Build the app for production
npm run build

# Run tests
npm test

📝 Notes
Ensure the app_location and output_location in the YAML workflow match your project structure.

The default React build output is in build/.

You can update the deployment settings in the Azure Portal if needed.

🔗 Links
Azure Static Web Apps Documentation

GitHub Actions Documentation

✅ Author: Oluwayemisi Okunrounmu
📅 Last Updated: October 2025
