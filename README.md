# Next.js template

A frontend template built on top of Next.js, shipped with TypeScript,
TailwindCSS, ESLint and lint-staged.

## Quick Start

```bash
git clone git@github.com:nguyend-nam/nextjs--typescript--lint-staged.git my-project-name
cd my-project-name
pnpm i
```

Then, you can run the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the
result.

You can start editing the page by modifying `pages/index.tsx`. The page
auto-updates as you edit the file.

## Tech stack

- Core

  - [React](https://reactjs.org/)
  - [Next.js](https://nextjs.org/)

- Styling

  - [Tailwindcss](https://github.com/tailwindcss/tailwindcss)

- Type checking & linting

  - [TypeScript](https://www.typescriptlang.org)
  - [ESLint](http://eslint.org/)
  - [Prettier](https://prettier.io/)

- Package manager
  - [pnpm](https://pnpm.io/)

## Commit

A commit message should follow the format:

```
type(scope?): message
```

Here are examples of valid commit messages:

- `feat: implement profile picture upload`
- `style(products): adjust font size`
- `fix(order): fix form input validation`

The rules for commit messages and valid specified types can be found in the
`commitlint.config.js` file.

A Git hook has also been set up to automatically analyze and fix linting errors
before committing your code. If you wish to disable it or modify its behavior,
refer to the `lint-staged` section in the `package.json` file.
