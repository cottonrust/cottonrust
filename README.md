# Start from 0

1. Install bun

```sh
curl -fsSL https://bun.sh/install | bash # for macOS, Linux, and WSL
```

2. Install deps

```sh
bun install
```

3. Run dev server

```sh
bun dev
```

4. Enjoy at http://localhost:4321

## Edit content

All content is in the `src/pages/index.astro` file. Use `<Section>` and `<Link>` tags (see usage in the file or Props of the components).

## Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/ # static assets
├── src/
│   └── components/
│       └── Link.astro # link component
│       └── Section.astro # section component
│   └── layouts/
│       └── Layout.astro # main layout
│   └── pages/
│       └── index.astro # home page
|   └── styles/
|       └── global.css # global styles
|   └── .github/
|       └── workflows/
|           └── deploy.yml # deploy workflow to GitHub Pages
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command               | Action                                           |
| :-------------------- | :----------------------------------------------- |
| `bun install`         | Installs dependencies                            |
| `bun dev`             | Starts local dev server at `localhost:4321`      |
| `bun build`           | Build your production site to `./dist/`          |
| `bun preview`         | Preview your build locally, before deploying     |
| `bun astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `bun astro -- --help` | Get help using the Astro CLI                     |
