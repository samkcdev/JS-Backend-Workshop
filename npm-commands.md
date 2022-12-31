# Initialize package.json file

`npm init -y`

# Frontend

## Packages needed to run frontend code

- **nodemon** - `npm install -g nodemon`
- **TypeScript** - `npm install -g typescript`
- **Webpack** - `npm install webpack webpack-cli webpack-dev-server`

### Running the frontend typescript code

Open two different terminal windows and run these code
or it can added as a script in the package.json file

- watch typeScript file changes and compile ts to js: `tsc --watch`
- compile js file to main.js and reload the server on file change:
  `npx web-dev-server --mode="development"`

# Backend

## Packages needed to run backend code

- **Express** : `npm install express`
- **@types/express** : `npm install @types/express`
- **ts-node** : `npm install -g ts-node`
- **mysql2** : `npm install --save mysql2`
- **types/mysql2** : `npm install types/mysql2`

### Running the backend typescript code

`nodemon --exec ts-node TodoRouter.ts`

## Documentation files:

TypeScript: [TypeScript Docs][ts]
Express : [Express Docs][express]

[ts]: https://www.typescriptlang.org/docs/
[express]: https://expressjs.com/en/starter/installing.html
