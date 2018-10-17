# Svelte Progressive Web App

This is a project template for [Svelte](https://svelte.technology) apps.

## Get started

*You need to have [Node.js](https://nodejs.org) installed.*

```bash
git clone https://github.com/MarkKhramko/svelte-pwa

cd svelte-pwa
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.


## Deploying to the web

### Option 1 - using [now](https://zeit.co/now)

Install `now`:

```bash
npm install -g now
```

Then, from within your project folder:

```bash
now
```

As an alternative, use the [Now desktop client](https://zeit.co/download) and simply drag the unzipped project folder to the taskbar icon.

### Option 2 - using [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
npm run build
surge public
```
