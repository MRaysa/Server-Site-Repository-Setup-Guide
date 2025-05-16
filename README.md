# 🛠️ Full-Stack Project Setup Guide
This document covers the complete setup for both Server Site (backend) and Client-Cite (frontend) parts of a full-stack web application.

## 📦 Server Site – Setup Guide

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


```
## ⚛️ Client-Cite – React Frontend Setup

This project is a React-based frontend application scaffolded using **Vite**, styled with **Tailwind CSS**, and enhanced with **DaisyUI**. It also includes **React Router** for routing functionality.

---

## 🚀 Project Initialization

### ✅ Step 1: Create Project Using Vite

```bash
npm create vite@latest client-cite -- --template react
# Create project
npm create vite@latest client-cite -- --template react

# Go to project directory
cd client-cite

# Install base packages
npm install

# Install React Router
npm i react-router

# Install Tailwind CSS and DaisyUI
npm install tailwindcss @tailwindcss/vite
npm i -D daisyui@latest

# Start development server
npm run dev
```
# ✅ Full Command Summary

# Server setup
```bash
mkdir server-site
cd server-site
npm init -y
npm i express cors mongodb dotenv
npm install -g nodemon
nodemon index.js
```
# Client setup
```bash
npm create vite@latest client-cite -- --template react
cd client-cite
npm install
npm install react-router
npm install tailwindcss @tailwindcss/vite
npm install -D daisyui@latest
npx tailwindcss init -p
npm run dev

