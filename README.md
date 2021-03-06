# Meteor + Webpack + Vue (for a big web app)

Example meteor project featuring flow-router, code-splitting, vue.js components hot-reloading.

It looks like this:

![screenshot](preview.png?raw=true "Screenshot of the kickstart app")

With a todos list app example (with real-time reactivity):

![screenshot](preview2.png?raw=true "Screenshot of the example app")

Tested with Meteor 1.3.1

## Usage

```
npm install
meteor
```

The example app has two lazy loaded modules, thanks to webpack code-splitting. However, the flow-router routes are all included in the initial load.

All of your style files and most of your Vue components will be fully hot-reloaded (template, style and code). Only your app layout component should trigger an automatic page refresh.

A sample todos list app is included, featuring real-time reactivity thanks to meteor.

## TODO

- More helpful Readme.md
- Server-side rendering for progressive enhancement
- Server-side caching
- Unit Tests
- Make a node package?
