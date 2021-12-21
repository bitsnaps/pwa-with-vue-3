# Progressive Web Apps with Vue 3

This project is a demo of the popular [TodoMVC](https://todomvc.com/) project using Vue3 with PWA plugin, to store data locally into your browser for better offline experience.

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Lints and fixes files

```
yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

## Add PWA plugin
Using Vue-CLI:
```
vue add pwa
```

## Config WPA
Create a `vue.config.js` file to configure the pwa files (like: `manifest.json`).
More options at [vue-cli doc](https://cli.vuejs.org/core-plugins/pwa.html).

## Storage
This demo uses IndexedDB (embedded database browser) to store and retreive data in offline mode.

Source: https://www.vuemastery.com/courses/progressive-web-apps-vue-3
