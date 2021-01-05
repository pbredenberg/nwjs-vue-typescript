# NW.js + Vue.js 3 + TypeScript

A starter project for NW.js desktop apps with Vue.js 3 and TypeScript.

Also includes ESLint + Prettier, and a unit test stub.

## NW.js Stuff

This project was created on macOS, so this currently expects your dev environment to be macOS, and that the NW.js executable can be found in your home folder at:

`~/nwjs/nwjs.app/Contents/MacOS/nwjs`.

## Project setup

```bash
npm install
```

### Compiles and hot-reloads for development

```bash
npm run serve
```

### Compiles and minifies for production

```bash
npm run build
```

### Launches the app in NW.js

```bash
npm run nwjs
```

NOTES:

- Assumes macOS, and that NWJ is installed in your home folder. See notes above.
- `localhost:8081` is set to the open in the main NW.js window, so in order for this to work
  you need to have already started `npm run serve`.

### Run your unit tests

```bash
npm run test:unit
```

### Lints and fixes files

```bash
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

## Packaging the App For Production

For right now, you're on you're own. NW.js has a good deal of documentation on this topic,
so no bundling strategy is included in this project.
