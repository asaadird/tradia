# Tradia

A modern full-stack e-commerce application built with React, TypeScript, and Supabase.

## About

Tradia is an e-commerce platform featuring product browsing, shopping cart management, user authentication, and secure checkout functionality.

## Technologies

- **Frontend**: React with TypeScript
- **Build Tool**: Vite
- **UI Components**: shadcn-ui
- **Styling**: Tailwind CSS
- **Backend & Database**: Supabase
- **Authentication**: Supabase Auth

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version 16 or higher)
- npm (comes with Node.js) or [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

## Getting Started

Follow these steps to get the project running locally:

### 1. Clone the Repository


### 2. Install Dependencies


This command will install all required packages listed in `package.json`.

### 3. Set Up Environment Variables

Create a `.env` file in the root directory and add your Supabase credentials:


### 4. Start the Development Server


This command starts the local development server with hot module replacement (HMR). Your application will automatically reload when you make changes to the code.

The application will be available at `http://localhost:5173` (or another port if 5173 is busy).

## Available Scripts

- `npm run dev` - Starts the development server with hot reload
- `npm run build` - Creates a production-ready build
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## Project Structure


## Features

- User authentication (signup, login, logout)
- Product catalog browsing
- Shopping cart functionality
- Secure checkout process
- Responsive design for mobile and desktop

## Development

The development server provides:
- Hot Module Replacement (HMR) for instant updates
- TypeScript type checking
- Fast refresh for React components

To stop the development server, press `Ctrl+C` in your terminal.

## Building for Production

To create an optimized production build:


The built files will be in the `dist/` directory, ready for deployment.

## License

This project is open source and available under the MIT License.

## Author

Created by [asaadird](https://github.com/asaadird)
