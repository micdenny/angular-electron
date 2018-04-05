# Build Angular Desktop Apps With Electron (QuickStart)

Check the [blog post](https://dennymichael.net/2018/04/05/build-angular-desktop-apps-with-electron/) to re-create this sample from scratch, step by step.

## Run in electron using a local file (without hot code reload support)

* Run `npm run electron-build` to build the project and run the application inside electron platform.

## Run in electron using a local dev server (WITH hot code reload support)

* Uncomment the code `mainWindow.loadURL('http://localhost:4200');` in the file `main.js` and comment out `mainWindow.loadURL(...dist/index.html...)`
* Run `npm start` for a dev server.
* Run `npm run electron` in a separated terminal, to run the application inside electron platform.

The app will automatically reload if you change any of the source files.

## Create a package for a native Windown application

* Run `npm run electron-package-win`.

Now you can run the executable `angular-electron.exe` you found under the folder `angular-electron-win32-x64`.

## Based on [Jeff Delaney](https://github.com/codediodeio)'s sample (Thank you!)

Here's [Jeff's post](https://angularfirebase.com/lessons/desktop-apps-with-electron-and-angular/), you can also check the [video lesson](https://youtu.be/u_vMChpZMCk) on youtube and the [original source code](https://github.com/AngularFirebase/angular-electron) on github.
