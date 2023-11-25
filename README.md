# my-electron-app

Welcome to my-electron-app, an Electron-based application designed for Ubuntu.
This simple guide will help you understand how to set up, run, and build the application as an AppImage, 
along with customizing the application name as it appears in the Ubuntu application bar.

### Setup
**Install Dependencies:**
   ```bash
   npm install
   ```

### Running the Application
To run the application in development mode, use:
```bash
npm start
```

## Customizing Application Name
To change the application name that appears in the Ubuntu application bar:

1. Open the `package.json` file.
2. Modify the `name` field to your desired application name.
   ```json
   "name": "my-electron-app-test",
   ```
3. Save your changes.

## Building as an AppImage
To build your application as an AppImage, suitable for distribution:

1. Run the build script:
   ```bash
   npm run build
   ```

This will generate an AppImage file in the `dist` directory.
The prefix of the name of the AppImage will be `name-version.AppImage` where the `name` and `version` are derived from the `package.json`
