# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)


## To install

- npm create vite@latest
- npm install

## https://tailwindcss.com/docs/guides/vite
- npm install -D tailwindcss
- npx tailwindcss init

## create tailwind.config.js
module.exports = {
  content: [
    "./index.html",
    "./src/**/*.{vue,js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

## create src/input.css
@tailwind base;
@tailwind components;
@tailwind utilities;

## terminal 
npx tailwindcss -i ./src/main.css -o ./dist/main.css --watch

## npm run dev

## Google fonts 
- https://github.com/google/material-design-icons
