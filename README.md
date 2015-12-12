# Hologram Github Theme Example

This is an example web application using [Hologram](https://github.com/trulia/hologram) with the [Hologram Github Theme](https://github.com/wearecube/hologram-github-theme) to generate a styleguide.

## Prerequisites

Assuming you have Ruby with Bundler and NPM/Node installed:

```
bundle install
npm install
```

## Building

To build the app with the styleguide:

```
npm run build
```

The styleguide can then be found in the ```styleguide/``` directory, the app in the ```dist/``` directory.

To start server with live-reload and open the styleguide in a browser:

```
npm run serve:styleguide
```
