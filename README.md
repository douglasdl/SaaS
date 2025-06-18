# SaaS with Next.js and RBAC

## Project Setup and Permissions

### Introduction

- [NextJS](https://nextjs.org/)

### Create Monorepo with TurboRepo

- [Turborepo](https://turborepo.com/)

Create the project:
```sh
pnpm dlx create-turbo@latest
```

### Prettier & ESLint in the Monorepo

```sh
cd config/prettier
pnpm i -D prettier
pnpm i -D prettier-plugin-tailwindcss

cd config/eslint-config
pnpm i -D @rocketseat/eslint-config
pnpm i -D eslint-plugin-simple-import-sort
```

### SaaS multi-tenant & RBAC

- RBAC: Role Based Authorization Control
- ABAC: Attribute Based Authorization Control

### Create the Authentication Package

### CASL Introduction

- [CASL](https://casl.js.org/v6/en/)

### Create the First Permissions