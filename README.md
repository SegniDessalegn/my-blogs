<p align="center">
  <a href="https://blogs.segni.dev" target="_blank">
    <img  src="./assets/images/dark.png">
  </a>
</p>

<h1 align="center">Nuxt Blog A Personal Blog Site</h1>

### Built with

<p align="center">
    <img width="200" src="./assets/images/logo.png">
</p>

 Nuxt Blog built with [Nuxt3](https://nuxt.com), [Nuxt-Content2](https://content.nuxtjs.org/blog/announcing-v2/), [Vue3](https://vuejs.org) & [TailwindCss](https://tailwindcss.com/)

## Features
- Write blog with markdown file
- Auto generate category from blog post
- Blog list page with search and pagination
- About me page for user info
- Auto generate table of content for blog post
- Auto generate Sitemap
- Url preview with Nuxt ogImage
- Dark and light mode
- Server Side Rendered(SSR) with Nuxt3

## Preview

<p align="center">
  <a href="https://blogs.segni.dev" target="_blank">
    <img width="1090" src="./assets/images/preview1.png">
    <img width="1090" src="./assets/images/preview2.png">
    <img width="1090" src="./assets/images/preview3.png">
    <img width="1090" src="./assets/images/preview4.png">
    <img width="1090" src="./assets/images/preview5.png">
    <br>
    Live Demo
  </a>
</p>

## Demo

https://blogs.segni.dev

> Hosted on [Vercel](https://vercel.com/): `npm run build`

## Build Setup

**Requires Node.js 16+**

```bash
# install dependencies
yarn install

# serve in dev mode, with hot reload at localhost:21446
yarn run dev

# build for production
yarn run build

# serve in production mode
yarn run  preview

```

The Draftbit preview expects port 21446. Start the sandbox server with
`./node_modules/.bin/nuxt dev --port 21446 --host 0.0.0.0`.
Pass flags directly to Nuxt; Yarn's extra `--` separator can cause the CLI to
ignore them and choose a different port.
