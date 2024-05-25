---
title: "Development Setup Handbook"
description: "General handbook for software engineers for day-to-day reference"
date: "Dec 05 2022"
demoURL: "https://learn-with-me.github.io/Development-Setup-Handbook/"
repoURL: "https://github.com/learn-with-me/Development-Setup-Handbook"
---

![Astro Sphere Lighthouse Score](/astro-sphere.jpg)

Astro Sphere is a static, minimalist, lightweight, lightning fast portfolio and blog theme based on my personal website.

It is primarily Astro, Tailwind and Typescript, with a very small amount of SolidJS for stateful components.

## 🚀 Deploy your own

<div class="flex gap-2">
  <a target="_blank" aria-label="Deploy with Vercel" href="https://vercel.com/new/clone?repository-url=https://github.com/markhorn-dev/astro-sphere">
    <img src="/deploy_vercel.svg" />
  </a>
  <a target="_blank" aria-label="Deploy with Netlify" href="https://app.netlify.com/start/deploy?repository=https://github.com/markhorn-dev/astro-sphere">
    <img src="/deploy_netlify.svg" />
  </a>
</div>

## 📋 Features

- ✅ 100/100 Lighthouse performance

## 💯 Lighthouse score
![Astro Sphere Lighthouse Score](/lighthouse.png)

## 🕊️ Lightweight
All pages under 100kb (including fonts)

## ⚡︎ Fast
Rendered in ~40ms on localhost

## 📄 Configuration

The blog posts on the demo serve as the documentation and configuration.

## 💻 Commands

All commands are run from the root of the project, from a terminal:

Replace npm with your package manager of choice. `npm`, `pnpm`, `yarn`, `bun`, etc

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run sync`            | Generates TypeScript types for all Astro modules.|
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
| `npm run lint`            | Run ESLint                                       |
| `npm run lint:fix`        | Auto-fix ESLint issues                           |

## 🏛️ License

MIT