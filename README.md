# E-Commerce React App

A modern e-commerce platform built with React, featuring product browsing, cart management, and user authentication.

## Features

- Product browsing (Computers, Mobiles, Laptops, Accessories)
- Shopping cart functionality
- User authentication (Login/Signup)
- Responsive design
- GitHub Pages deployment

## Tech Stack

- React 18
- React Router DOM
- Vite
- CSS3
- GitHub Actions for CI/CD

## Local Development

1. Clone the repository
2. Install dependencies: `npm install`
3. Start development server: `npm run dev`
4. Open http://localhost:5173

## Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions. The deployment process:

1. Builds the project using Vite
2. Deploys to GitHub Pages using the `actions/deploy-pages` action
3. Available at: https://thiruveedulachandrasekhar.github.io/CICD-EXP1/

## Project Structure

- `/src/components/` - React components
- `/src/context/` - React context providers
- `/src/services/` - API services
- `/public/` - Static assets
- `/.github/workflows/` - GitHub Actions configuration

## Notes

- The app uses client-side routing with React Router
- GitHub Pages is configured to handle SPA routing via 404.html redirect
- All static assets are properly configured for the `/CICD-EXP1/` base path
