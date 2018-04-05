# Build Angular Desktop Apps With Electron (QuickStart)

Check the [blog post](https://dennymichael.net/2018/04/05/build-angular-desktop-apps-with-electron/) to re-create this sample from scratch, step by step.

## Run in electron using a local file (without hod code reload support)

* Run `npm run electron-build` to build the project and run the application inside electron platform.

## Run in electron using a local dev server (WITH hod code reload support)

* Run `npm start` for a dev server.
* Run `npm run electron` in a separated terminal, to run the application inside electron platform.

The app will automatically reload if you change any of the source files.

## Create a package for a native Windown application

* Run `npm run electron-package-win`.

Now you can run the executable `angular-electron.exe` you found under the folder `angular-electron-win32-x64`.
