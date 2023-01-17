# Sandbox

## Gatsby DevServer Looping Reproduction Steps

1. Run `nvm use` to set your session's node version.
2. Run `npm install` to install the repo dependencies.
3. Run `npx nx serve myblog` to run the `myblog` gatsby application in the NX mono repo.
4. (alternative) run `npm exec gatsby develop --workspace=gatsby-starter-default` to run the `myblog` gatsby application circumventing the nx runners.
5. Observe dev server logs re-building the development bundle without active code changes.
