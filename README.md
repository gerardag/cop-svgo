# SVGO CLI Lab

The goal of this lab is getting familiar with SVG optimization tool. It's a really simple, effective library and super easy to use.

## Installing

First of all, you need to clone this repo:

```sh
$ git clone https://github.com/gerardag/cop-svgo
```

After that, install [`svgo`](https://github.com/svg/svgo) using npm or yarn, what you prefer:

```sh
$ npm install -g svgo
```

Or yarn:

```
$ yarn global add svgo
```

After the installation process and setting up the environment, you need to copy `svg-originals` folder into new one, for example `svg`:

```sh
$ cp svg-originals svg
```

## First activity

The first activity will be optimize all `.svg` files from a folder. In this case, we use the `svg` folder files. For that purpose, you need to run just the following command:

```sh
$ svgo svg/
```

When executed, this automatically removes all unnecessary code for `.svg` files and will be printed into terminal with the optimization made for every single file.

