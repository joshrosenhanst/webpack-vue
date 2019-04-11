# Webpack-Vue

A starter kit for a [Vue.js](https://vuejs.org) and [Webpack](https://webpack.js.org/) project.

- ES2015+ and .vue file support via [babel 7](https://babeljs.io/)
- Sass support via [sass-loader](https://github.com/webpack-contrib/sass-loader)
- Linting via [eslint-loader](https://github.com/webpack-contrib/eslint-loader) and React Eslint config.
- Image support via [file-loader](https://github.com/webpack-contrib/file-loader)

## Directories

- `src/public` - All assets in this directory will be copied into the `dist/assets/` directory.
- `src/assets` - Static assets that will be imported into the project on demand. File loader will automatically move them into `dist/assets/`
- `src/index.js` - Vue entry point.
- `src/App.vue` - The main App component which loads sub-components.
- `src/index.html` - The HTML template that is used to render Vue.

## Build Scripts
- `npm run build` - Build development bundle in the `dist` directory. Assets are placed in the `dist/assets/` directory.
- `npm run start` - Run Webpack Dev Server which automatically reloads on CSS/JS changes.
- `npm run production` - Build production bundle with minified code.