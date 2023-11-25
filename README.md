# My-Electron-App

Welcome to `my-electron-app`, a research-focused Electron application designed to explore how to rename the application name in Ubuntu's application bar.

## Getting Started

### Prerequisites
Ensure [Node.js](https://nodejs.org/) is installed on your system to proceed with the setup.

### Setup
**Install Dependencies:**
Initialize your development environment by installing necessary dependencies:
```bash
npm install
```

### Running the Application
**Development Mode:**
Launch the application in development mode with:
```bash
npm start
```
This will start the Electron app, enabling real-time observation of your modifications.

## Customizing the Application Name

**Modifying the Display Name in Ubuntu:**
1. Access the `package.json` file in your project's root.
2. Alter the `name` field to your chosen application name, from
   ```json
   "name": "my-electron-app",
   ```
   to:
   ```json
   "name": "my-electron-app-hepta-is-good",
   ```
3. Save these changes to apply the new application name.

## Building as an AppImage

**Generating a Distributable AppImage:**
Execute the build script to create an AppImage for distribution:
```bash
npm run build
```
An AppImage will be created in the `dist` directory, following this naming format:
```
$name-$version.AppImage
```
The `$name` and `$version` values are pulled from the `package.json`.
