# Sveltekit-Typescript-TailwindCSS-Jit

This template project is based on the official (**beta**) SvelteKit template (see [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte)), but, on top, includes

- TypeScript
- Less CSS
- TailwindCSS with the brand new JIT (just-in-time) compiler mode up and running 😎.

Adding Tailwind-classes, hot-reloading and `@apply` should work as expected (tested under Windows).

## Note

Please note that SvelteKit is still in public beta, as explained in [this blogpost by Rich Harris](https://svelte.dev/blog/sveltekit-beta).

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

Svelte apps are built with _adapters_, which optimise your project for deployment to different environments.

By default, `npm run build` will generate a Node app that you can run with `node build`. To use a different adapter, add it to the `devDependencies` in `package.json` making sure to specify the version as `next` and update your `svelte.config.cjs` to [specify your chosen adapter](https://kit.svelte.dev/docs#configuration-adapter). The following official adapters are available:

- [@sveltejs/adapter-node](https://github.com/sveltejs/kit/tree/master/packages/adapter-node)
- [@sveltejs/adapter-static](https://github.com/sveltejs/kit/tree/master/packages/adapter-static)
- [@sveltejs/adapter-netlify](https://github.com/sveltejs/kit/tree/master/packages/adapter-netlify)
- [@sveltejs/adapter-vercel](https://github.com/sveltejs/kit/tree/master/packages/adapter-vercel)
- ...more soon

[See the adapter documentation for more detail](https://kit.svelte.dev/docs#adapters)
