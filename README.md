# Boilerplate template for typescript project

A base template for building typescript projects. Included dependencies are:

- Typescript
- Typescript compiler
- TS-Node
- TS-Mocha
- Nodemon

# Quick start

Included are scripts to execute, compile and run tests in your typescript project.

```
# Execute
npm start

# Compile
npm run compile

# Test
npm test
```

# Publishing

If you wish to publish archetypes to a repository, you should do the following to publish:

1. Update `package.json` setting `name` to the correct repository to publish to.

2. Execute the following commands
```
export NPM_TOKEN=<your_repository_token>
npm run compile
npm run deploy
```

N.B. - If you wish to publish to a different repository other than NPM registry then you should update the `.npmrc` to the correct repository.
