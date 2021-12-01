# Blogging Platform

A blogging platform that allows users to create blogs with a default subdomain and the option to add a custom domain (usually with a premium monthly subscription).

### Demo

For context, here's a starter kit of a blogging platform built on Vercel:

- [steven.platformize.co](https://steven.platformize.co)
- [vercel.platformize.co](https://vercel.platformize.co)
- [retreat.platformize.co](https://retreat.platformize.co)
- [stey.me](https://stey.me) (custom domain)
- [vercel.pub](https://vercel.pub) (custom domain)
- [retreat.vercel.pub](https://retreat.vercel.pub) (custom subdomain)
- [app.platformize.co](https://app.platformize.co) (editing backend)

All of these generated sites are powered by ISR (no SSR at all) so they load pretty much instantly + the inter-page transitions are lightning fast.

### Features

- 🔀 Hostname Rewrites
- 📍 Custom Domains API
- ✍️ Markdown Text Editor

### Real-world examples

- [Hashnode](https://hashnode.com/)
- [Medium](https://medium.com/)

### How to Use

You can choose from one of the following two methods to use this repository:

**One-Click Deploy**

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel-customer-feedback/edge-functions/tree/main/examples/hostname-rewrites&project-name=hostname-rewrites&repository-name=hostname-rewrites)

**Clone and Deploy**

Download this repository via git:

```bash
git clone https://github.com/vercel-customer-feedback/edge-functions.git
```

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example edge-middleware/examples/hostname-rewrites hostname-rewrites
# or
yarn create next-app --example edge-middleware/examples/hostname-rewrites hostname-rewrites
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=edge-middleware-eap) ([Documentation](https://nextjs.org/docs/deployment)).

> 💡 Do note that you will need to replace the `ROOT_URL` variable in the `.env.example` file with your domain of choice and add that domain as a wildcard domain your Vercel project.