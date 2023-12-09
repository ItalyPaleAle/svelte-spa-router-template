<table>
  <tr>
    <td>
      <a href="https://www.amazon.com/dp/B08D6T6BKS/"><img src="https://static.packt-cdn.com/products/9781839213625/cover/smaller" width="120" /></a>
    </td>
    <td>
      <h3>Svelte 3 Up and Running</h3>
      <p>Want to learn Svelte 3 and how to build a Single-Page App (SPA) with it (and with this router)? Check out my book <a href="https://www.amazon.com/dp/B08D6T6BKS/">Svelte 3 Up and Running</a> on Amazon.</p>
    </td>
</table>

# Svelte app with svelte-spa-router

This is a project template for [Svelte 4](https://svelte.dev) apps that includes [svelte-spa-router](https://github.com/italypaleale/svelte-spa-router) for client-side routing, TypeScript, and Vite as bundler.

## About svelte-spa-router

svelte-spa-router is a client-side router for Svelte 4 apps that leverages hash-based routing (i.e. stores the current view in the URL after the `#` symbol).

You can read more about the router, and the reasons why you might want to use hash-based routing (or not), in the [documentation](https://github.com/italypaleale/svelte-spa-router).

## Get started

Install the dependencies…

```bash
cd svelte-app
npm install
```

…then start a dev server using [Vite](https://vite.dev):

```bash
npm run dev
```

Navigate to [http://localhost:5050](http://localhost:5050). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

You can add more routes by defining them in the [`src/routes.ts`](./src/routes.ts) file. More information can be found on the [documentation for svelte-spa-router](https://github.com/ItalyPaleAle/svelte-spa-router/blob/main/README.md).

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `vite` commands in package.json to include the option `--host 0.0.0.0`.

If you're using [Visual Studio Code](https://code.visualstudio.com/) we recommend installing the official extension [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode). If you are using other editors you may need to install a plugin in order to get syntax highlighting and intellisense.

## Building and running in production mode

To create an optimized version of the app:

```bash
npm run build
```

You can run the newly-built app with `npm run preview`.
