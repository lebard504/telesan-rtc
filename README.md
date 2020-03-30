## Get Started

1. **Install [Node 8](https://nodejs.org)** or newer. Need to run multiple versions of Node? Use [nvm](https://github.com/creationix/nvm)
2. **Navigate to this project's root directory on the command line.**
3. **Install Node Packages.** - `npm install`
4. **Install [React developer tools in Chrome](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en) and Eslint, Prettier components for VisualCode.**
5. Having issues? See below.

## Having Issues? Try these things first:

1. Run `npm install` - If you forget to do this, you'll get an error when you try to do `npm start` the app later.
2. Don't run the project from a symbolic link. It will cause issues with file watches.
3. Delete any .eslintrc in your user directory and disable any ESLint plugin / custom rules within your editor since these will conflict with the ESLint rules defined in the course.
4. On Windows? Open your console as an administrator. This will assure the console has the necessary rights to perform installs.
5. Ensure you do not have NODE_ENV=production in your env variables as it will not install the devDependencies. To check run this on the command line: `set NODE_ENV`. If it comes back as production, you need to clear this env variable.
6. Nothing above work? Delete your node_modules folder and re-run npm install.

### Production Dependencies

| **Dependency**                  | **Use**                                                          |
| ------------------------------- | ---------------------------------------------------------------- |
| bluebird                        | Full featured Promises/A+ implementation.                        |
| classnames                      | A simple utility for conditionally joining classNames together.  |
| express                         | Minimalist web framework for node.                               |
| lodash                          | Lodash modular utilities.                                        |
| socket.io                       | Node.js realtime framework server.                               |
| socket.io-client                |  is exposed automatically by the socket.io server.               |


### Development Dependencies

| **Dependency**                  | **Use**                                                          |
| ------------------------------- | ---------------------------------------------------------------- |
| eslint                          | Lints JavaScript.                                                |
| eslint-config-airbnb            | Lints configuration with AirBNB integration.                     |
| eslint-config-airbnb-base       | Airbnb's base JS ESLint config.                                  |
| eslint-plugin-import            | Lints plugin.                                                    |
| nodemon                         | Simple monitor script for use during development of a node.js.   |