# Elder.js Template Project

This is a project template for [Elder.js](https://elderguide.com/tech/elderjs/) apps. The template lives at https://github.com/elderjs/template and the Elder.js source is here: https://github.com/elderjs/elderjs

Here is a demo of the template: [https://elderjs.netlify.app/](https://elderjs.netlify.app/)

## Get started

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit Elderjs/template elderjs-app
cd elderjs-app
```


### Install the dependencies:

```bash
npm install # or just yarn
```

### Start Project:

```bash
npm start
```

Navigate to [localhost:3000](http://localhost:3000). You should see your app running. 


### Development:

For development, we recommend running two separate terminals. One for the server and the other for rollup.

**Terminal 1**

```bash
npm run dev:server # `npm start` above starts a server, but doesn't rebuild your Svelte components on change.
```

**Terminal 2**

```bash
npm run dev:rollup # This rebuilds your svelte components on change.
```

Once you have these two terminals open, edit a component file in `src`, save it, and reload the page to see your changes.

### To Build HTML:

```bash
npm run build
```

This will build all of your html into the /public/ folder. 


### What to Expect

This template is designed to be part demo, part tutorial. We hope you enjoy if you hit snags please create a GitHub issue. :)

<img width="1452" alt="image" src="https://user-images.githubusercontent.com/3580879/89454786-358ba380-d72f-11ea-975a-1c0a6aa5a37e.png">
