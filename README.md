# MonoRepo Example

This monorepo example uses yarn workspaces, read more about setting up yarn
workspaces [here](https://classic.yarnpkg.com/en/package/workspaces).

In order to install all packages in monorepo, remove in `/packages` folder in
paackages all `node_modules` and `package-lock.json` files.

Make sure that in root level `package.json` `"private"` flag is set to `true`
and that it has `workspaces` flag added like this:
`"workspaces": ["packages/*"],`.

## Install packages in monorepo

To install npm packages in all packages that thisa monorepo setup has, run
`yarn` in root of commandline.

## Run packages in monorepo

To run Monorepo packages in dev mode execute in your terminal 'yarn start`.

**Happy Coding!!**
