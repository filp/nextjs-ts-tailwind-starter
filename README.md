# nextjs-ts-tailwind-starter

This is a [NextJS](https://nextjs.org/) starter template based off [`create-next-app`](https://nextjs.org/docs/api-reference/create-next-app), including:

- Typescript
- TailwindCSS
- Google Font (Roboto) embed under a custom `_document.tsx` file, and matching `tailwind.config.js`
- Custom `prettier` and `eslint` configuration
  - `prettier-plugin-tailwindcss` for automatic Tailwind class sorting
  - Import order rules
  - Enforce use of `type` modifier in imports when appropriate
  - Avoid `console.log` statements
  - Prefer arrow functions with implicit returns when appropriate
  - ...and a bunch of other rules
- Path aliases configured under `tsconfig.json` (`@components/`, `@lib/`)

## Using this starter

### With `create-next-app`:

```shell
$ npx create-next-app -e https://github.com/filp/nextjs-ts-tailwind-starter
```

### With `degit`:

```shell
$ npx degit https://github.com/filp/nextjs-ts-tailwind-starter <your-app-name>
```
