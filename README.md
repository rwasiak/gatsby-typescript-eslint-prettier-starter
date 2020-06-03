<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby's typescript-eslint-prettier starter
</h1>

## 🛠 Features

1. [TypeScript](https://www.typescriptlang.org/) support
2. CSS in JS - [Styled components](https://www.styled-components.com/)
3. ESlint [Airbnb React/JSX style guide](https://github.com/airbnb/javascript/tree/master/react) and [jsx-a11y rules](https://github.com/jsx-eslint/eslint-plugin-jsx-a11y)
4. [Stylelint](https://stylelint.io/) - styles linter compatible with styled-components
5. Pre-Commit Hooks - [Husky](https://github.com/typicode/husky) and [lint-staged](https://github.com/okonet/lint-staged)

## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the default starter.

    ```shell
    # create a new Gatsby site using the starter
    gatsby new my-default-starter https://github.com/rwasiak/gatsby-typescript-eslint-prettier-starter
    ```

2.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```shell
    cd my-default-starter/
    gatsby develop
    ```

3.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

    _Note: You'll also see a second link: _`http://localhost:8000/___graphql`_. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql)._

    Open the `my-default-starter` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

## 🧐 What's inside?

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── node_modules
    ├── src
    ├── .eslintignore
    ├── .eslintrc
    ├── .gitignore
    ├── .prettierignore
    ├── .prettierrc
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    └── README.md

1.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages) are automatically installed.

2.  **`/src`**: This directory will contain all of the code related to what you will see on the front-end of your site (what you see in the browser) such as your site header or a page template. `src` is a convention for “source code”.

3.  **`.eslintrc`**: This is a configuration file for [ESlint](https://https://eslint.org//). ESLint statically analyzes your code to quickly find problems.

4.  **`.eslintignore`**: This file tells [ESlint](https://https://eslint.org//) to ignore specific files and directories.

5.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

6.  **`.prettierrc`**: This is a configuration file for [Prettier](https://prettier.io/). Prettier is a tool to help keep the formatting of your code consistent.

7.  **`.prettierignore`**: This file tells [Prettier](https://prettier.io/) to exclude specific files and directories from formatting.

8.  **`.stylelintrc`**: This is a configuration file for [Stylelint](https://stylelint.io/). This linter helps you avoid errors and enforce conventions in your styles.

9.  **`gatsby-browser.js`**: This file is where Gatsby expects to find any usage of the [Gatsby browser APIs](https://www.gatsbyjs.org/docs/browser-apis/) (if any). These allow customization/extension of default Gatsby settings affecting the browser.

10. **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://www.gatsbyjs.org/docs/gatsby-config/) for more detail).

11. **`gatsby-node.js`**: This file is where Gatsby expects to find any usage of the [Gatsby Node APIs](https://www.gatsbyjs.org/docs/node-apis/) (if any). These allow customization/extension of default Gatsby settings affecting pieces of the site build process.

12. **`gatsby-ssr.js`**: This file is where Gatsby expects to find any usage of the [Gatsby server-side rendering APIs](https://www.gatsbyjs.org/docs/ssr-apis/) (if any). These allow customization of default Gatsby settings affecting server-side rendering.

13. **`LICENSE`**: Gatsby is licensed under the MIT license.

14. **`package-lock.json`** (See `package.json` below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t change this file directly).**

15. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

16. **`README.md`**: A text file containing useful reference information about your project.

17. **`tsconfig.json`**: This is a configuration file for [TypeScript](https://www.typescriptlang.org/index.html). This file specifies the root files and the compiler options required to compile the project.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.org/).
