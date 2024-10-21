# ContactManagement

The ContactManagement is a Frondend project which interacts with .NET Core Web API designed to manage contacts with robust CRUD operations. 
CRUD Operations: Supports Create, Read, Update, and Delete operations for managing contacts along with Sorting and Pagination.

This project was generated with Angular CLI version 16.2.16.

## Table of Contents
- Development Server
- Code Scaffolding
- Build Process
  - Prerequisites
  - Development Build
  - Production Build
  - Build Options
  - Serving the Build Locally
  - Hosting the Build
- Running Unit Tests
- Running End-to-End Tests
- Further Help

## Development Server

To run a development server:

ng serve

Navigate to http://localhost:4200/. The application will automatically reload if you change any of the source files, enabling hot-reload for a smooth development experience.

## Code Scaffolding

Use Angular CLI commands to scaffold new components, services, or other code structures:

ng generate component component-name

Similarly, you can generate other Angular artifacts, such as:

ng generate directive|pipe|service|class|guard|interface|enum|module

## Build Process

### Prerequisites

Ensure you have the following prerequisites installed:

1. Node.js and npm: Download Node.js at https://nodejs.org/, which includes npm.
2. Angular CLI: Ensure Angular CLI is installed globally:

npm install -g @angular/cli

3. Dependencies: Run the following command to install project dependencies:

npm install

### Development Build

For a development build with live reload, run:

ng build --configuration=development

This will build the project and place the build artifacts in the dist/ directory, optimized for debugging.

### Production Build

For a production-ready build, optimized for performance:

ng build --configuration=production

Production builds are optimized with:
- Minification of JavaScript and CSS
- Tree-shaking to remove unused code
- Ahead-of-Time (AOT) compilation for faster runtime performance

The production build will output files in the dist/contact-management/ directory.

### Build Options

You can customize the build process using the following options:

- Source maps: Generate source maps for easier debugging of production builds:

ng build --configuration=production --source-map

- Base href: Specify a base URL for serving the application from a subdirectory:

ng build --base-href /sub-directory/

- Output hashing: Hash output filenames to ensure cache-busting:

ng build --output-hashing=all

- Other configurations: Customize build size limits, optimization options, and more by modifying the angular.json configuration file.

### Serving the Build Locally

To serve the production build locally and test the deployment:

1. Install the http-server package globally:

npm install -g http-server

2. Serve the build output:

http-server ./dist/contact-management/

3. Open http://localhost:8080/ to view the application running in a production-like environment.

### Hosting the Build

You can host the production build on any static web server or cloud-based hosting services such as:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Azure Static Web Apps

To deploy, simply upload the contents of the dist/contact-management/ folder to your hosting provider.

## Running Unit Tests

To run unit tests:

ng test

This command executes unit tests via Karma, providing a report of all the passing and failing tests in real-time. The test runner automatically reloads when it detects any changes in the test files.

## Running End-to-End Tests

To run end-to-end tests:

ng e2e

You need to install an end-to-end testing package first (such as Protractor or Cypress) to use this command. End-to-end testing simulates real user interactions with the app to ensure everything is functioning correctly.

## Further Help

For additional help or guidance on using the Angular CLI, run:

ng help

Or visit the Angular CLI Overview and Command Reference at https://angular.io/cli for detailed documentation.
