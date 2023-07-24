# vue3d
Easily view interactive 3d models in any vue app.


![Demo](demo.gif)
# Setup
1. Install @reidjs/vue3d from [npm](https://www.npmjs.com/package/@reidjs/vue3d) 


`npm i @reidjs/vue3d`

2. Import the `ModelViewer` component
```html
<script setup>
    import { ModelViewer } from "@reidjs/vue3d"
</script>

<template>
    <ModelViewer src="/plant.glb" auto-rotate camera-controls></ModelViewer>
<template>
```

# Docs
This package wraps google's [model-viewer](https://modelviewer.dev/) with vue, so refer to their docs for usage.

# Local development

Install issue
to install google model viewer you need:
    "@google/model-viewer": "^3.1.1",
    "three": "^0.151.2",
in package.json

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
