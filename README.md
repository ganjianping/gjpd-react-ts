# React + Typescript Demo

A minimal setup to get React working in Vite with HMR (Hot Module Replacement) and some ESLint rules.

## Table of Contents

1.  [Key Features](#key-features)
2.  [Quick Start](#quick-start)
3.  [Detailed Usage](#detailed-usage)
4.  [Development Guide](#development-guide)
5.  [Testing](#testing)

## Key Features

*   **React:** A JavaScript library for building user interfaces.
*   **TypeScript:** A superset of JavaScript that adds static typing.
*   **Vite:** A build tool that aims to provide a faster and leaner development experience for modern web projects.
*   **HMR:** Enables hot reloading during development for faster feedback loops.
*   **ESLint:** Integrated for code linting to maintain code quality.

## Quick Start

1.  **Install Dependencies:**
    ```bash
    npm install
    ```

2.  **Run the Development Server:**
    ```bash
    npm run dev
    ```
    This will start the Vite development server with HMR enabled. Open your browser to the indicated local URL.

## Detailed Usage

*   **Development Server:** `npm run dev` - Starts the development server.
*   **Build for Production:** `npm run build` - Compiles and bundles the application for production using TypeScript and Vite. The output is placed in the `dist` folder.
*   **Lint Code:** `npm run lint` - Runs ESLint to check for code style and potential errors.
*   **Preview Production Build:** `npm run preview` - Starts a local server to preview the production build from the `dist` folder.

## Development Guide

### Code Structure

*   `public/`: Static assets that are served directly.
*   `src/`: Contains the main application source code (React components, styles, etc.).
*   `index.html`: The main HTML entry point for the application.
*   `vite.config.ts`: Configuration file for Vite.
*   `tsconfig.json`, `tsconfig.node.json`: TypeScript configuration files.
*   `package.json`: Project metadata and dependencies.
*   `eslint.config.js`: ESLint configuration.

### Expanding ESLint Configuration

For more robust type-aware linting in production applications, consider updating `eslint.config.js`. Refer to the official ESLint and TypeScript-ESLint documentation for advanced configurations, including rules for React-specific best practices.

## Testing

Currently, this project template does not include a specific testing setup. You can integrate testing frameworks like Vitest, Jest, or React Testing Library based on your project requirements. Add testing scripts to your `package.json` accordingly.
