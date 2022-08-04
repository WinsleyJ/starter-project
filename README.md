# Starter

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Project setup

```bash
  npm install
```

### Compiles and hot-reloads for development

```bash
  npm run dev
```

### Compiles and minifies for production

```bash
  npm run build
```

```bash
  npm install
```

### Compiles and hot-reloads for development

```bash
  npm run dev
```

### Compiles and minifies for production

```bash
  npm run build
```

## Dependencies

The following dependencies are pre-installed:

- Vue
- Vue Router
- Vue GTM (Google Tag Manager)

## DevDependencies

The following dev dependencies are pre-installed:

- Vite
- Autoprefixer
- PostCSS
- TailwindCSS

## Vue Router

You don't have to initialize the router first, that is already done. You can just add your routes to the router. You can also add routes to the router by adding them to the `routes` array in the `/src/router/index.js` file. There are already 2 routes defined in the router:

- Home
- Page not found

The `Home` route is the default route, it will be the first route that is loaded when the user visits the site. The `Page not found` route is the route that is loaded when the user visits a route that does not exist. Because both are necessary routes, they are already created in the router.

## Vue GTM

In the `src/main.js` file you will find the configuration of the GTM object. Don't forget to add your GTM ID to the GTM object and to change 'debug' to 'false' when you are ready to deploy your site.

## Comments

There are some comments in the template starting with `TODO:` as a simple reminder. Some of the comments include a link to a tool online to help you with the specific todo. Once your done with the task you can simple remove the comment. Search `TODO:` through all files to make sure you didn't miss any of them.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
