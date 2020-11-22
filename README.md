# svelte33

This is a project template for a single-page Svelte web site. 

It has SASS, Bootstrap 4, and works out-of-the-box at Netlify, see [these instructions](https://onespace.netlify.app/howtos?id=332) for publishing at Netlify.

It also reads from a JSON file, and allows the user to search the items via text box with results shows as they type, which demonstratoes how to use events and the interaction between components.

```bash

npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.

## Set-up

Clone this code to a local directory, then:

```bash
npm install
npm run dev
```