# React Boilerplate

<p align="center">
  <a href="https://travis-ci.org/matAlmeida/react-boilerplate"><img src="https://travis-ci.org/matAlmeida/react-boilerplate.svg?branch=master" alt="build status"></a>
  <a href="https://coveralls.io/github/matAlmeida/react-boilerplate?branch=master"><img src="https://coveralls.io/repos/github/matAlmeida/react-boilerplate/badge.svg?branch=master" alt="code coverage"></a>
  <a href="https://github.com/webpack/webpack"><img src="https://aleen42.github.io/badges/src/webpack.svg" alt="webpack"></a>
  <a href="https://github.com/prettier/prettier"><img src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg" alt="prettier"></a>
  <a href="https://github.com/airbnb/javascript"><img src="https://img.shields.io/badge/eslint-airbnb-4B32C3.svg" alt="airbnb-style"></a>
</p>
<br />

A `React` boilerplate using

- Sass
- Webpack
- Prettier
- Jest / Enzyme
- ESLint with `Airbnb` style

## Instruction

```bash
$ git clone https://github.com/matAlmeida/react-boilerplate.git YourProjectName
$ cd YourProjectName
$ npm install
$ npm start
```

## Scripts

| script                  | what it does                                             |
| ----------------------- | -------------------------------------------------------- |
| `npm install`           | Install the projects dependencies                        |
| `npm start`             | Run the development server on `localhost:3000`           |
| `npm test`              | Run al tests suites on `test/` folder                    |
| `npm run build`         | Build a optmized bundle for production on `dist/` folder |
| `npm run lint`          | Run the linter on the `src/` folder                      |
| `npm run lint -- --fix` | Fix some linter problems                                 |
| `npm run coverage`      | Run code coverage test                                   |
