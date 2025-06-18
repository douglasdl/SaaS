# SaaS with Next.js and RBAC

## Project Setup and Permissions

### Introduction

- [NextJS](https://nextjs.org/)

### Create Monorepo with TurboRepo

- [Turborepo](https://turborepo.com/)

Create the project:
```sh
npx create-turbo@latest
```

### Prettier & ESLint in the Monorepo

```sh
cd config/prettier
npm i -D prettier
npm i -D prettier-plugin-tailwindcss

cd config/eslint-config
npm i -D @rocketseat/eslint-config
npm i -D eslint-plugin-simple-import-sort
```