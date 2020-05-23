<h3 align="center"><a href="https://fab.dev"><img width="190" alt="FAB Examples" src="https://user-images.githubusercontent.com/23264/82729969-24b4bf80-9cf4-11ea-8056-ee129eb08d09.png"></a>
</h3>

This is the https://github.com/nuxt/content project converted to [Frontend Application Bundles](https://fab.dev), deployed to [Cloudflare Workers](https://workers.dev) using [Linc](https://linc.sh):

<h3 align="center"><a href="https://nuxt-content-docs.linc.workers.dev/">ht&#8203;tps://nuxt-content-docs.linc.workers.dev/</a></h3>

* See the [code changes required](https://github.com/nuxt/content/compare/master...fab-examples:master) to make this work
* [Get started](https://fab.dev/guides/getting-started) yourself with FABs
* Then, configure Linc for [automatic Cloudflare Workers releases](https://linc.sh/docs/cloudflare-workers)

---

![nuxt-content](https://user-images.githubusercontent.com/904724/80923202-7a93e880-8d82-11ea-8ae1-044ebdc80aac.png)

# @nuxt/content

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Github Actions CI][github-actions-ci-src]][github-actions-ci-href]
[![Codecov][codecov-src]][codecov-href]
[![License][license-src]][license-href]

> @nuxt/content lets you write in a content/ directory, acting as Git-based Headless CMS

- [🎲 Play on CodeSandbox](https://codesandbox.io/s/nuxtcontent-demo-l164h?)
- [🎬 Demonstration videos](https://content.nuxtjs.org/#videos)
- [✨ Release Notes](https://github.com/nuxt/content/releases)
- [📖 Read the documentation](https://content.nuxtjs.org)

## Features

- Blazing fast hot reload in development
- Vue components in Markdown
- Full-text search
- Support static site generation with `nuxt generate`
- Powerful QueryBuilder API (MongoDB like)
- Syntax highlighting to code blocks in markdown files using PrismJS.
- Table of contents generation
- Handles Markdown, CSV, YAML, JSON(5)
- Extend with hooks

[📖 Read the documentation](https://content.nuxtjs.org)

## Development

1. Clone this repository
2. Install dependencies using `yarn install` or `npm install`
3. Start development server using `yarn dev` or `npm run dev`

## License

[MIT License](./LICENSE)

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/@nuxt/content/latest.svg
[npm-version-href]: https://npmjs.com/package/@nuxt/content

[npm-downloads-src]: https://img.shields.io/npm/dt/@nuxt/content.svg
[npm-downloads-href]: https://npmjs.com/package/@nuxt/content

[github-actions-ci-src]: https://github.com/nuxt/content/workflows/ci/badge.svg
[github-actions-ci-href]: https://github.com/nuxt/content/actions?query=workflow%3Aci

[codecov-src]: https://img.shields.io/codecov/c/github/nuxt/content.svg
[codecov-href]: https://codecov.io/gh/nuxt/content

[license-src]: https://img.shields.io/npm/l/@nuxt/content.svg
[license-href]: https://npmjs.com/package/@nuxt/content
