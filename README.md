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

2. Navigate to `html-sass-webpack-boilerplate` folder.

3. Install all dependencies.

   ```
   $ npm install
   ```

## Development

Start a development server.

```
$ npm start
```

The development server will open the browser automatically and you should see your site live.

## Folders structure

- All `*.html` files should be placed directly in `dist/` folder.
- Images and other static files that don't need to be processed with webpack should be placed in `dist/static` folder.
- `*.js` development files in `src/js` folder.
- `*.scss` and `*.css` files in `src/styles` folder.
- Fonts, images which are used in css as `url('')` must be placed in `src/assets` folder.

### Example

```
root
│
├── dist
│   ├── index.html
│   └── static
│        └── image.png
├── src
│   │
│   ├── assets
│   │   ├── background.svg
│   │   └── Lato-bold.woff
│   │
│   ├── js
│   │   ├── app.js
│   │   └── index.js
│   │
│   └── styles
│       ├── _base.scss
│       ├── _variable.scss
│       └── main.scss
│
other root files ...
```

## Build

```
$ npm run build
```

The files ready to upload to server will be found in `dist/` folder.

## Serving files locally

Now files from `dist` folder can be served on the local network by the local server.

```
$ npm run serve
```

## Formating code

```
$ npm run format
```

The files `*.js` and `*.scss` in `src/` folder, and `*.html` files in `dist/` folder will be formatted with [Prettier](https://prettier.io/)
