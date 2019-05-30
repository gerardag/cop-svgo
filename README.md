# SVGO Lab

![SVG logo](https://cdn-images-1.medium.com/max/800/0*PFeo13wnAp318LKY.png)

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

## Main activity

The first activity will be optimize all `.svg` files from a folder. In this case, we use the `svg` folder files. For that purpose, you need to run just the following command:

```sh
$ svgo svg/
```

When executed, this automatically removes all unnecessary code for `.svg` files and will be printed into terminal with the optimization made for every single file.

## Next steps

After the first contact with the svg library, you can play with all the rest of the options that library provides to you:

- Optimize just one file
- Optimize all the files from a diferents directory using regexp: `svgo *.svg`
- Optimize and copy all the new files into diferent directory: `svgo -f svg-originals\ -o svg-optimized`

## Bonus

Also, you can use a web version of this plugin. You just need to upload `.svg` file or paste the markup and download the optimized result.

https://jakearchibald.github.io/svgomg/
