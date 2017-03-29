# Electorn & ReactJS

## [Electron && ReactJS tutorial reference](https://medium.freecodecamp.com/building-an-electron-application-with-create-react-app-97945861647c#.pybnm7n4t)

## To compile project:

Before you compile this project, you need to comment this line:
`
mainWindow.webContents.openDevTools();
`
inside ./src/electron/electron-starter.js

Then, you need to have installed electron-packager globaly

```
npm install -g electron-packager
```

### Windows x86
```
react-scripts build && electron-packager . 'Electron & ReactJS' --platform=win32 --arch=ia32 --out=electron_builds/win32
```

### Windows x64
```
react-scripts build && electron-packager . 'Electron & ReactJS' --platform=win32 --arch=x64 --out=electron_builds/win32
```
