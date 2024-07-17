# React Library CRA Template
This is a template intended to be used with the [create-react-app](https://www.npmjs.com/package/create-react-app) tool. It contains methods of building and publishing your library to npm.
For now, the library makes use of React 18 and does not use TypeScript. To apply the template, run the following command:

```npx create-react-app [library-name] --template @ptolemy2002/react-library```

## Commands
The following commands exist in the project resulting from applying this template:
- `npm run build` - Builds the library
- `npm run release` - Publishes the library to npm without changing the version
- `npm run release-patch` - Publishes the library to npm with a patch version bump
- `npm run release-minor` - Publishes the library to npm with a minor version bump
- `npm run release-major` - Publishes the library to npm with a major version bump