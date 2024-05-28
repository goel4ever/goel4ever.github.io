# Personal portfolio

Personal portfolio built with Astro Nano.

Astro Nano is a static, minimalist, lightweight, lightning fast portfolio and blog theme.
Built with Astro, Tailwind and Typescript, no frameworks.

It was designed as an even more minimal theme than my popular theme [Astro Sphere](https://github.com/markhorn-dev/astro-sphere)

## 📋 Features

- ⚡︎ Rendered in ~40ms on localhost
- ✅ Auto generated sitemap
- ✅ Auto generated RSS Feed
- ✅ MDX Support (components in your markdown)

![Astro Nano Lighthouse Score](_lighthouse.png)

## 📄 Configuration

The blog posts on the demo serve as the documentation and configuration.

## 💻 Development

All commands are run from the root of the project, from a terminal:

Replace npm with your package manager of choice. `npm`, `pnpm`, `yarn`, `bun`, etc

| Command                    | Action                                           |
|:---------------------------| :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm run dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm run dev:network`     | Starts local dev server on local network         |
| `pnpm run sync`            | Generates TypeScript types for all Astro modules.|
| `pnpm run build`           | Build your production site to `./dist/`          |
| `pnpm run preview`         | Preview your build locally, before deploying     |
| `pnpm run preview:network` | Preview build on local network                   |
| `pnpm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm run astro -- --help` | Get help using the Astro CLI                     |
| `pnpm run lint`            | Run ESLint                                       |
| `pnpm run lint:fix`        | Auto-fix ESLint issues                           |
