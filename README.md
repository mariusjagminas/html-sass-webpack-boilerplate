# HTML SASS Webpack Boilerplate

Simple frontend boilerplate to build web projects easily.

## How to develop web projects with this boilerplate

### Prerequisites

You must have [Node.js](https://nodejs.org/en/) installed on your system.

## Installation

1. Clone the boilerplate to your local machine.

   ```
   $ git clone https://github.com/mariusjagminas/html-sass-webpack-boilerplate.git
   ```

2. Install all dependencies.

   ```
   $ npm install
   ```

## Development

3. Start a development server.

   ```
   $ npm start
   ```

The dev server will open the browser automatically.

## Folders structure

- The development files `*.js` and `*.scss` are in the `src/` folder.

- `*.html` files are in `dist/` folder.

- Images should be stored in `assets/` folder.

```
root
│
├── dist
│   ├── index.html
│   └── assets
│
└── src
    │
    ├── js
    │   ├── app.js
    │   └── index.js
    │
    └── styles
        ├── _base.scss
        ├── _variables.scss
        └── main.scss
```

## Build

```
$ npm run build
```

The compiled files will be placed in the `dist/` folder.

## Formating code

```
$ npm run format
```

The files `*.js` and `*.scss` in `src/` folder, and `*.html` files in `dist/` folder will be formatted with [Prettier](https://prettier.io/)
