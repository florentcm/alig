# 🐊 Alig - Another Lorem Ipsum Generator

[![Netlify Status](https://api.netlify.com/api/v1/badges/f01e8196-a5e0-4c01-b317-6b3ad1861b72/deploy-status)](https://app.netlify.com/sites/alig/deploys)

## 🎉 Getting Started

1. 👯‍♂️ Clone the repository locally and cd into the directory.

```bash
git clone https://github.com/xdesro/nuxt-netlify-cms-starter

cd nuxt-netlify-cms-starter
```

2. 📦 Install dependencies.

```bash
yarn install
```

3. 🏗 Run the project for local dev. This will start a hot-reloading server at `localhost:3000`.

```bash
yarn dev
```

4. 🌌 Build the app for server-side rendered deployment. See more about **Universal SSR** in the [Nuxt.js docs](https://nuxtjs.org/guide#server-rendered-universal-ssr-).

```bash
yarn build

# And to serve that deployment...
yarn start
```

5. ⚡️ Generate a fully pre-rendered static site. See more [in the docs](https://nuxtjs.org/guide#static-generated-pre-rendering-).

```bash
yarn generate
```

> This project was bootstrapped with `create-nuxt-app`. There are more detailed explanations of how everything works in the [Nuxt.js docs](https://nuxtjs.org).

## 🖋 Activating Netlify CMS

This project comes with Netlify CMS ready to rumble, and a basic blog configuration. To use Netlify CMS:

### 🔏 Authenticating with Netlify Identity

1. Deploy to Netlify at least once.
2. Go to **Settings > Identity**, and select **Enable Identity service**.
3. Once enabled, select **Settings and usage**, and scroll down to **Registration preferences**. You can set this to either **Open** or **Invite only**, but usually **Invite only** is your best bet for a personal site.
4. If you don't want to create an account, or would like to use an external provider such as GitHub or Google, you can enable those services under **External providers**.
5. Scroll down to **Services** and click **Enable Git Gateway**.

### 🔏 Media configuration
The default configuration expects you to run on Netlify's Large Media, which uses Git LFS. To configure this yourself read up on it here:
* [documentation](https://docs.netlify.com/large-media/overview/)
or directly set it up by following [these](https://docs.netlify.com/large-media/setup/#configure-file-tracking) steps

### 🔐 Local Setup

1. In your browser, navigate to `localhost:3000/admin`.
2. Enter the Netlify URL of your site when prompted. (when using a different domainname host, use be sure to use the URL as provided by Netlify, not your domain host)
3. Login with the account you created or one of the external providers, if you enabled them.

## 💁‍♀️ Questions? Concerns?


