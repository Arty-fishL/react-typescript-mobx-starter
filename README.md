# IMPORTANT: WIP - NOT YET FUNCTIONAL!

---

# React Typescript MobX Starter

> Minimal starter with hot module replacement (HMR) for rapid development.

- **[React](https://facebook.github.io/react/)** (16.x)
- **[Webpack](https://webpack.js.org/)** (4.x)
- **[Typescript](https://www.typescriptlang.org/)** (3.x)
- **[MobX](https://mobx.js.org/)** (4.15.x)
- **[Hot Module Replacement (HMR)](https://webpack.js.org/concepts/hot-module-replacement/)** using [React Hot Loader](https://github.com/gaearon/react-hot-loader) (4.x)
- [Babel](http://babeljs.io/) (7.x)
- [React Router](https://reacttraining.com/react-router/) (5.x)
- [Mobx Utils](https://github.com/mobxjs/mobx-utils) (5.x)
- [Mobx React](https://github.com/mobxjs/mobx-react) (6.x)
- [Mobx React Router](https://github.com/alisd23/mobx-react-router) (4.x)
- [SASS](http://sass-lang.com/) using [sass-loader](https://github.com/webpack-contrib/sass-loader) (8.x)
- [Jest](https://facebook.github.io/jest/) (25.x) - Testing framework for React applications
- [Enzyme](https://enzymejs.github.io/enzyme/) (3.x) - Testing framework for React applications
- [jest-extended](https://github.com/jest-community/jest-extended) (0.11.x) - TODO
- [Prettier](https://prettier.io/) (1.x) - TODO
- Production build script
- Image loading/minification using [Image Webpack Loader](https://github.com/tcoopman/image-webpack-loader)
- Typescript compiling using [Awesome Typescript Loader](https://github.com/s-panferov/awesome-typescript-loader) (5.x)
- Code quality (linting) for Typescript.

## Installation

1. Clone/download repo
2. `yarn install` (or `npm install` for npm)

## Usage

**Development**

`yarn start`

- Build app continuously (HMR enabled)
- App served @ `http://localhost:8080`

**Production**

`yarn start:prod`

- Build app once (HMR disabled) to `/dist/`
- App served @ `http://localhost:3000`

---

**All commands**

| Command           | Description                                                                   |
| ----------------- | ----------------------------------------------------------------------------- |
| `yarn start:dev`  | Build app continuously (HMR enabled) and serve @ `http://localhost:8080`      |
| `yarn start:prod` | Build app once (HMR disabled) to `/dist/` and serve @ `http://localhost:3000` |
| `yarn build`      | Build app to `/dist/`                                                         |
| `yarn test`       | Run tests                                                                     |
| `yarn lint`       | Run Typescript linter                                                         |
| `yarn lint:fix`   | Run Typescript linter and fix issues                                          |
| `yarn start`      | (alias of `yarn start:dev`)                                                   |

**Note**: replace `yarn` with `npm run` in `package.json` if you use npm.

## See also

- [React Webpack Babel Starter](https://github.com/vikpe/react-webpack-babel-starter)
- [Isomorphic Webapp Starter](https://github.com/vikpe/isomorphic-webapp-starter)
