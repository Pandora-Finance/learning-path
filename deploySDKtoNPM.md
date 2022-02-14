# Publishing SDK to NPM Registry

- Create an account on [npm](https://www.npmjs.com/) website.
- Choose a unique name for your package. Can verify by searching on npm registry website, that the desired name is not assigned to another package.
- Go to `package.json` file in SDK code & Enter the desired name for the package in `name` field along with `version`, by default it would be `1.0.0`
- Open terminal to sign in to npm, enter `npm login`, you’ll be prompted to enter your username, password, and email address.
- Enter `npm publish` command in terminal to publish the package to npm.