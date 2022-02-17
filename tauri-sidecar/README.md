# Sidecar example

This example demonstrates how to use the Tauri sidecar feature. It uses [pkg](https://github.com/vercel/pkg) to compile a Node.js application and bundle it on the Tauri application.

## Running the example

- Install [nvm](https://github.com/nvm-sh/nvm)

- Install dependencies (Run inside of this folder `sidecar/`)
```bash
$ nvm install
$ nvm use

# with yarn
$ yarn
# with npm
$ npm install

$ yarn tauri
$ yarn package
```

- Run the app in development mode (Run inside of this folder `sidecar/`)
```bash
# with yarn
$ yarn tauri dev
# with npm
$ npm run tauri dev
```

- Build an run the release app (Run inside of this folder `sidecar/`)
```bash
$ yarn tauri build
```
