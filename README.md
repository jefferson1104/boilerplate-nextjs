<center>

![BoilerPlate](public/img/icon-192.png)

## NextJS Boilerplate

</center>

This is a boilerplate to be use in your project with tecnologies TypeScript, NextJS, Storybook, Styled-components, Jest and React-testing-library.
## What is inside?

This project uses lot of stuff as:

- [TypeScript](https://www.typescriptlang.org/)
- [NextJS](https://nextjs.org/)
- [Styled Components](https://styled-components.com/)
- [Jest](https://jestjs.io/)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro)
- [Storybook](https://storybook.js.org/)
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Husky](https://github.com/typicode/husky)

## Getting Started
```bash
# Creating your project using this boilerplate
$ yarn create next-app -e https://github.com/jefferson1104/boilerplate-nextjs PROJECT_NAME

# Install dependencies
$ yarn

# Run local project
$ yarn dev

# Tests
$ yarn test

# Generate component
$ yarn generate COMPONENT_NAME
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Init Husky in your project
Execute command: `npx husky-init && yarn`

In the **pre-commit** file inside the .husky directory **.husky/pre-commit** Change line content `npm test` to `npx --no-install lint-staged`

## Commands

- `dev`: runs your application on `localhost:3000`
- `build`: creates the production build version
- `start`: starts a simple server with the build production code
- `lint`: runs the linter in all components and pages
- `test`: runs jest to test all components and pages
- `test:watch`: runs jest in watch mode
- `storybook`: runs storybook on `localhost:6006`
- `build-storybook`: create the build version of storybook
- `generate`: create the component structure in an automated way

