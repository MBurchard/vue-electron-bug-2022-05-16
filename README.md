# vue-electron-bug-2022-05-16

## Project setup

This project work with `--legacy-peer-deps` only.

```
npm i --legacy-peer-deps
```

### Compiles and hot-reloads for development

All fine in development mode with `electron:serve`

```
npm run electron:serve
```

### The Problem...

Build Electron App

```
npm run electron:build
```

switch into `dist_electron/win-unpacked` folder and start the application.

You'll see Home | About and a lot of white screen...  
Home is not loading.

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
