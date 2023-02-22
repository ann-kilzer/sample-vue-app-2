# sample-vue-app

This template should help get you started developing your website with Vue 3 in Vite.

It includes:

- [Vite](https://vitejs.dev/) for building
- [Vuetify](https://vuetifyjs.com/en/)
- [Vitest](https://vitest.dev/)
- [ESLint](https://eslint.org/)

## Prerequisites

- Node 18
- A GitHub account

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
   1. Run `Extensions: Show Built-in Extensions` from VSCode's command palette
   2. Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

### Type check

```sh
npm run type-checkde
```

### Run unit tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### How to deploy your website to GithubPages

1. In `vite.config.ts` file add your repository name in `base`.
2. In `package.json` edit `website` adding your GitHub handle and repository name.
3. Build your website by running `npm run build` command.
4. Deploy to GitHub pages by running `npm run deploy` command.
5. Check your website on the url you added in `website`. It may take a few minutes to deploy.
