# Web OpcUA Manager (webopcuamanager)

A web-based OPC UA Client developed with Node.js and the Quasar Framework, featuring a modern responsive UI and cross-platform accessibility through any browser.js

GitHub: <https://github.com/SEB103/WebOpcUaManager.git>

## Git Setup for WebOpcUaManager

## Global setup

- git config --global user.name "Your Name"
- git config --global user.email <your.email@example.com>

## Create a new repository (WebOpcUaManager)

- git clone <https://github.com/SEB103/WebOpcUaManager.git>
- cd WebOpcUaManager
- touch README.md
- git add README.md
- git commit -m "add README"
- git push -u origin master

## Push an existing folder

- cd existing_folder
- git init
- git remote add origin <https://github.com/SEB103/WebOpcUaManager.git>
- git add .
- git commit -m "Initial commit"
- git push -u origin master

## Push an existing Git repository

- cd existing_repo
- git remote rename origin old-origin
- git remote add origin <https://github.com/SEB103/WebOpcUaManager.git>
- git push -u origin --all
- git push -u origin --tags

## Quasar CLI Cheat Sheet (NPM only)

### Install the dependencies

- npm install

### Development / Start the app in development mode (hot-code reloading, error reporting, etc.)

- quasar dev

### Lint the files / Run ESLint checks

- npm run lint

### Format the files / Run Prettier formatting

- npm run format

### Type check (TS projects)

- npm run type-check (Usually runs `vue-tsc --noEmit`)

### Build the app for production

- `quasar build` (SPA / PWA / SSR / Electron / Capacitor)
- `quasar serve` dist/spa (Static file server for testing production build)

### Customize the configuration

- Main configuration file: [`quasar.config.js`] <https://v2.quasar.dev/quasar-cli-vite/quasar-config-js>.
- Used to set build options, dev server, plugins, boot files, CSS preprocessors, etc.

## Useful Notes

- Quasar CLI manages multiple modes in a single project (SPA, PWA, SSR, Electron, Capacitor, Cordova, BEX).
- Recommended setup for long-term projects:
  - **TypeScript** → Yes
  - **Pinia (state management)** → Yes
  - **ESLint + Prettier** → Yes
- Update Quasar dependencies with:

```bash
  npm update quasar
  npm update @quasar/app-vite
```
