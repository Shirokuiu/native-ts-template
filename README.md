## Support
Development:
- Live reload
- Typescript
- Scss

Linting:
- Eslint,
- Husky,
- Lint staged

## Install dependencies

```shell script
npm install
```

## Development

For development, you can use the command that runs webpack dev server:

```shell script
npm run serve
```

## Build 

For build your application, run command:

```shell script
npm run build
```

For build your application on production, run command:

```shell script
npm run build:prod
```

After buld, 3 files will be generated in the dist folder:

- index.html
- bundle.js
- style.css

The `assets` folder, which will contain all the necessary files.

## Add libraries

For add libraries you can use command:

```shell script
npm add <lib-name>
``` 

## Add polyfills

For add polyfills you can use [core-js](https://github.com/zloirock/core-js):

```shell script
npm add core-js
``` 

IE10 and IE11 requires the following for NgClass support on SVG elements

```shell script
npm add classlist.js
``` 
