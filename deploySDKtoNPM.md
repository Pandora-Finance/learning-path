# Publishing SDK to NPM Registry

- Create an account on [npm](https://www.npmjs.com/) website.
- Choose a unique name for your package. Can verify by searching on npm registry website, that the desired name is not assigned to another package.
- Go to `package.json` file in SDK code & Enter the desired name for the package in `name` field along with `version`, by default it would be `1.0.0`
![package.json image](/images/package_json.jpg "Package.json image")
- Open terminal to sign in to npm, enter `npm login`, you’ll be prompted to enter your username, password, and email address.
![npm login screen image](/images/npm_login.jpg "NPM login screen")
- Enter `npm publish` command in terminal to publish the package to npm.

# Updating the SDK to new version
When changes are made to SDK code & need to update it on SDK.

- Visit SDK homepage on npm registry ie, `https://www.npmjs.com/package/<PACKAGE_NAME>`
- Check for the latest version deployed.
- Now, increment the version based on the type of update or release on `package.json` file's version field.
![package.json version](/images/version.jpg "package.json version")
- Enter `npm publish` command in terminal to publish the changes to npm.