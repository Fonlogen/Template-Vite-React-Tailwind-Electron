# Javascript VRTE Template
A template repository pre-configured with Vite + React, TailwindCSS and Electron with JavaScript

## Configuration
Remember to configure the package.json based on your needs
Install all the dependencies using ```yarn install```

## Scripts
This template uses YARN as package manager. Remember to instal yarn globally using the follwing command:
```npm install -g yarn```

## Pre-configured Scripts

### ```yarn dev```
Starts the VITE Development Server with default configuration

### ```yarn dev-host```
Starts the VITE Development Server with the ```--host``` option, making the server available to the local network

### ```yarn build```
Builds the aplication with VITE. By default the build files will be stored in the ```dist``` directory

### ```yarn start-electron```
Starts electron based on the ```main.js``` file. Alternatively, you can start electron using the command ```electron main.js```.

### ```yarn build-bin-win```
Builds the binaries for Windows OS using ```electron-builder```

### ```yarn build-bin-mac```
Builds the binaries for MacOS using ```electron-builder```

### ```yarn build-bin-linux```
Builds the binaries for Linux OS using ```electron-builder```
By default the Linux binaries will created for Debian/Ubuntu based distros (```.deb```). You can configure more builds by editing the ```electron-builder.json``` file

