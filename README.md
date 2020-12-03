# XtendOps Status Check

[![Production Website](https://img.shields.io/website?label=Production&url=https%3A%2F%2Fstatus.xtendops.com%2F)](https://status.xtendops.com/)
[![XO](https://img.shields.io/badge/Powered%20by-XtendOPS%20DEV%20Team-blue)](http://developers.xtendops.com/)

Inspired by Github Status(https://www.githubstatus.com/)

## Setup

```bash
npm install
```

## Development

```bash
npm run start:dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.

If you're using [Visual Studio Code](https://code.visualstudio.com/) we recommend installing the official extension [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode). If you are using other editors you may need to install a plugin in order to get syntax highlighting and intellisense.

## Production

```bash
npm run build
```

You can run the newly built app with `npm run start`. This uses [sirv](https://github.com/lukeed/sirv), which is included in your package.json's `dependencies` so that the app will work when you deploy to platforms like [Heroku](https://heroku.com).

### Single-page app mode

By default, sirv will only respond to requests that match files in `public`. This is to maximise compatibility with static fileservers, allowing you to deploy your app anywhere.

If you're building a single-page app (SPA) with multiple routes, sirv needs to be able to respond to requests for *any* path. You can make it so by editing the `"start"` command in package.json:

```js
"start": "sirv public --single"
```

## Resources

- https://github.com/sveltejs/template
- https://svelte.dev
- https://github.com/sveltejs/component-template


<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://crrmacarse.github.io / 139.59.100.139"><img src="https://avatars3.githubusercontent.com/u/39759024?v=4" width="100px;" alt=""/><br /><sub><b>Macarse, Christian Ryan R.</b></sub></a><br /><a href="https://github.com/xtendops-developers/api/commits?author=crrmacarse" title="Code">💻</a> <a href="https://github.com/xtendops-developers/api/commits?author=crrmacarse" title="Documentation">📖</a> <a href="#infra-crrmacarse" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#question-crrmacarse" title="Answering Questions">💬</a> </td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

---

If you have any concerns and questions, please contact the development team

Read our Developer Guidelines [here](https://developers.xtendops.com/docs) or visit our developer website via https://developers.xtendops.com/
