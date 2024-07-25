# React Library CRA Template
This is a template intended to be used with the [create-react-app](https://www.npmjs.com/package/create-react-app) tool. It contains methods of building and publishing your library to npm.
For now, the library makes use of React 18 and does not use TypeScript. To apply the template, run the following command:

```npx create-react-app [library-name] --template @ptolemy2002/react-library```

Note that, because of how create-react-app works, dependencies are installed on the root directory automatically and package.json is set up. This is not necessary for either the library or the example, as those are each subdirectories of the root directory. node_modules, package.json, and package-lock.json on the root directory are safe to delete.

## Commands
The following commands exist in the project resulting from applying this template:
- `npm run uninstall` - Uninstalls all dependencies for the library
- `npm run reinstall` - Uninstalls and then Reinstalls all dependencies for the library
- `npm run example-uninstall` - Uninstalls all dependencies for the example app
- `npm run example-install` - Installs all dependencies for the example app
- `npm run example-reinstall` - Uninstalls and then Reinstalls all dependencies for the example app
- `npm run example-start` - Starts the example app after building the library
- `npm run build` - Builds the library
- `npm run release` - Publishes the library to npm without changing the version
- `npm run release-patch` - Publishes the library to npm with a patch version bump
- `npm run release-minor` - Publishes the library to npm with a minor version bump
- `npm run release-major` - Publishes the library to npm with a major version bump