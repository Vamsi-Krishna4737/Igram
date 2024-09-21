# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


# iGram Frontend

This project is the front-end of the iGram application, built using React, Vite, and Material-UI for a modern, responsive UI. It includes form validation with Formik and Yup, and client-side routing with React Router. Tailwind CSS is used for utility-first styling.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Scripts](#scripts)
- [Environment Variables](#environment-variables)
- [Dependencies](#dependencies)
- [License](#license)

## Features

- Built with React 18 and Vite for fast development
- Material-UI components for consistent design
- Form validation using Formik and Yup
- Client-side routing using React Router
- Responsive layouts using Tailwind CSS
- OTP (One-Time Password) input using MUI One-Time Password Input
- Axios for handling HTTP requests

## Prerequisites

- Node.js and npm installed
- A back-end server (like the iGram API)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/igram-frontend.git


Scripts:-
npm run dev: Starts the Vite development server.
npm run build: Builds the project for production.
npm run lint: Runs ESLint to check for code quality issues.
npm run preview: Previews the production build locally.

Dependencies:-
@mui/material: Material-UI React components.
axios: Promise-based HTTP client for the browser and Node.js.
formik: Form library for React.
react-router-dom: Declarative routing for React apps.
yup: JavaScript schema builder for value parsing and validation.
mui-one-time-password-input: OTP input for Material-UI.


Dev Dependencies:-
@vitejs/plugin-react: Official Vite plugin for React.
eslint: Linting utility for JavaScript/React code.
tailwindcss: Utility-first CSS framework.
vite: Next-generation front-end tooling.