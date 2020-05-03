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

The development file should be placed in a folder according to its type.

```
 src
 |
 ├── assets // Images, fonts and icons.
 |
 ├── js // All JavaScript files.
 |
 ├── styles // SASS, CSS files.
 |
 └── templates // HTML files.
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

The development files in `src/` folder will be formatted with [Prettier](https://prettier.io/)
