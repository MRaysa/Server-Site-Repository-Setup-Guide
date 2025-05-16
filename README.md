# 📦 Server Site – Setup Guide

This project is a simple Express.js server setup using Node.js, MongoDB, and environment variable support via dotenv. This guide walks you through the entire setup process step by step.

---

## 📁 Project Initialization

Open your terminal or command prompt and follow these steps:

```bash
# Create a new directory for your server
mkdir server-site

# Navigate into the project directory
cd server-site

# Initialize a new Node.js project with default settings
npm init -y

# 📦 Install Required Packages
# Run the following command to install the necessary dependencies:
npm i express cors mongodb dotenv
# 🧪 Run the Server Using Nodemon
#If nodemon is installed globally on your system:
nodemon index.js
# If not installed globally, you can install it by running:
npm install -g nodemon
# 📝 Update package.json Scripts
# Update the scripts section in package.json to make starting the server easier:
"scripts": {
  "start": "node index.js",
  "test": "echo \"Error: no test specified\" && exit 1"
}
