# devkit
DevKit is an opinionated framework-less framework for doing all the things which aims to offer a great DX (developer experience)


## Prerequisites

```
{"node":">=16.14"}`

==> node --version
v16.13.2

==> brew upgrade node

==> node --version
v16.18.1
```

## Steps for devkit-demo

* Boostrap dev-kit-demo using the following steps
```
==> cd dev-kit-demo

==> npm create svelte@latest dev-kit-demo
Need to install the following packages:
  create-svelte@latest
Ok to proceed? (y) y

create-svelte version 2.0.0-next.190

Welcome to SvelteKit!

This is release candidate software; expect bugs and missing features.

Problems? Open an issue on https://github.com/sveltejs/kit/issues if none exists already.

✔ Which Svelte app template? › Skeleton project
✔ Add type checking with TypeScript? › Yes, using TypeScript syntax
✔ Add ESLint for code linting? … No / Yes
✔ Add Prettier for code formatting? … No / Yes
✔ Add Playwright for browser testing? … No / Yes

Your project is ready!
✔ Typescript
  Inside Svelte components, use <script lang="ts">
✔ ESLint
  https://github.com/sveltejs/eslint-plugin-svelte3
✔ Prettier
  https://prettier.io/docs/en/options.html
  https://github.com/sveltejs/prettier-plugin-svelte#options
✔ Playwright
  https://playwright.dev

Install community-maintained integrations:
  https://github.com/svelte-add/svelte-adders

Next steps:
  1: cd dev-kit-demo
  2: npm install (or pnpm install, etc)
  3: git init && git add -A && git commit -m "Initial commit" (optional)
  4: npm run dev -- --open

To close the dev server, hit Ctrl-C

Stuck? Visit us at https://svelte.dev/chat
```
## Develop
* Run in dev mode using

```
==> npm install

==> npm run dev
```