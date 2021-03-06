# The Jitsi Handbook

This is The Jitsi Handbook. Your one-stop-shop for Jitsi documentation. It's powered by [Docusaurus](https://docusaurus.io/).

## Install dependencies

If you use **Windows**, you need to install ```gifsicle```:

```js 
npm install -g gifsicle
```
alternative command:
```js
cnpm install gifsicle
```

If you use **Debian/Ubuntu**, you need to install ```dh-autoreconf```:

```shell
apt-get update
apt-get install dh-autoreconf
```

If you use **MacOS**, you need to install ```automake```:

```shell
brew install automake
```

## Building the site

The site is built automatically with every push thanks to a [GH Actions](https://github.com/jitsi/handbook/blob/master/.github/workflows/gh-pages.yml).

If you want to build it locally, follow these simple steps:

```js
cd website
npm install
npm start
```

You can now edit the files in the `docs` folder and the site will reflect the changes immediately thanks to
live reloading.

## Contributing

We appreciate all contributions to this repository. Please make a Pull Request, no matter how small, all contributions
are valuable!
