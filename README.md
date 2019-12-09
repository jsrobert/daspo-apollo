# Daspo-Apollo

[![Netlify Status](https://api.netlify.com/api/v1/badges/e2bfca08-a76e-43ab-864f-751f34592c3a/deploy-status)](https://app.netlify.com/sites/gatsby-apollo-starter/deploys)

## Tech

- Apollo provider & Client side routing
- Eslint/Prettier configured
- Flex Grid components 

## Prerequisites

[Yarn](https://yarnpkg.com/en/)

Please create a new file `.env.development` and put this env variable with your GitHub token

> If you're building locally, you will have to create a new file `.env.production` and put the same env variable

```bash
GATSBY_GRAPHQL_API=xxxxxxxxxx
```

Don't forget to edit your site's data on `src/data/index.js` file

## Installing

Installing the dependencies

```bash
yarn
```

## Start the dev server

```bash
yarn start
```

### Clean the cache

This removes the `.cache/` & `public/` folders

```bash
yarn reset
```

## Built with

- Gatsby
- React
- GraphQL
- Apollo
- VSCode
-JavaScript libraries & Gatsby plugins [package.json](package.json)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Contributors

- [Myself](https://github.com/jsrobert/)


