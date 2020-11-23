# karamoff.dev  [![website status](https://badgen.net/uptime-robot/status/m782289871-06cf6e2f25dfd0855c64c874?label=&cache=300)](https://karamoff.dev)

The source code of my website (located at [karamoff.dev](https://karamoff.dev))

## Pre-install
sudo apt update
sudo apt upgrade

## Install node 12.x
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs

## Install yarn
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update && sudo apt install yarn

## Install gulp
npm install --global gulp-cli

## Install app
yarn install

## Build

To build the static version of the website in `public` directory:

```sh
yarn build
```

## Preview

To host the `public` directory:

```sh
yarn start
```

----

[![powered by Vercel](https://badgen.net/badge/host/powered%20by%20vercel/black?icon=now&label=)](https://vercel.com)
