---
title: TWS WordPress Theme
description: Quisque at magna posuere, auctor tellus sed, mollis erat. Pellentesque posuere non nulla sed dictum. Suspendisse ultricies massa enim, pulvinar luctus orci porttitor sed. Integer commodo lectus sed nunc hendrerit imperdiet. Integer interdum eu nibh sed sollicitudin. Donec in quam in ante consequat bibendum. Proin mattis leo et risus auctor, eget semper leo lacinia. Duis sem justo, vulputate quis tellus a, dapibus euismod tellus.
og:image: https://images.unsplash.com/photo-1706425278305-b9440b5fcd1f
date: 2022-11-12
tags: TWS, Test
---

# TWS WordPress Theme

The starting point for TWS theme development.

This theme is a work in progress and will need to be maintained.

This theme aims to include most parts that we have created during the development of other themes.
This is so we can reuse and restyle them without being forced to write duplicate code or looking for other sites to copy code from.
**If you have made a new part in another theme add it to this one.**

## Requirements

- [Node.js](https://nodejs.org/en/) (For **Mac** recommended install is via Homebrew, for **Linux** recommended install is via the CLI)

## TWS

After you have made your project using this template, link your repository to the matching Slack channel using the following command in Slack.

```
/github subscribe TheWebsiteSpace/PROJECT_NAME
```

_You may need to invite GitHub to the channel first with `/invite @github`._

## Guides

### How to Use This Theme Template

Click the big green "Use This Template" button and input the new project name.
To use this theme, navigate to this theme directory and run the command `npm run start`.
_More information can be found in [Node.js Commands](#Node-js-commands)._

#### Editing `.css`

You can edit the websites `.css` in the `/styles` folder.
This folder uses `.sass` files which get compiled into a single `.css`.
_If you don't know how to use `.sass` then check out the documentation [here](https://sass-lang.com/documentation)._
When you add a new `.sass` file to `/styles/parts` you will need to include it in the `/styles/main.sass` file or it won't be compiled.

#### Editing `.js`

`.js` is edited in the websites `/scripts` folder.
When creating new `.js` files in `/scipts/parts` you must manually import them into `/scripts/main.js`.
`/scripts/main.js` uses a Node.js extension to import files which your compiler will not like, _ignore most errors on this page_.

#### Editing WordPress `functions.php`

`functions.php` has been split up for readability using PHP's built-in `include` functions.
The files used in `functions.php` can be found in `/includes`.
If you add a new file inside `/indudes` you must import it in the respective `_all.php` file.

---

### Node.js Commands

Node.js is being used for speeding up development and for creating a final Oliver server ready theme.
There are various commands that can be seen in `package.json`, here is how to use them.

#### Setting Up

```
npm run init
```

This command will update the browserslist database and then proceed to run the `npm run compile` command to compile all the template `.sass` and `.js` files into the distribution files `/dist/main.css` and `/dist/main.js` respectively.
`npm run compile` also runs `npm run touch` which simply initialised `/dist/custom.css` and `/dist/custom.js` which is used to make changes to websites after they have gone live.

#### Development

```
npm run start
```

This command starts a gulp process that spins up a local website portal on [localhost:3000](localhost:3000) that watches for any changes being made in files of type `.sass`, `.scss`, `.js` and `.php`, and live updates the local website.

#### Getting Ready for Production

```
npm run prod
```

This command is to be used when website development is complete and you want to create a production ready theme without all the faff.
This command cleans then recompiles the development theme.
It then initialises a new folder labelled `tws_theme`, for which it them copies every file from the development folder.
Afterwards it removes the development files such as the `/node_modules`, `/styles` and `/scripts` folders.

After the command has finished you simply need to select it in `WordPress Site > Appearance > Themes` and remove the development theme.

## Future plans

- Unit testing

## Contributors

<!-- If you have commited to the development of this theme template add yourself to the hall of fame (in alphabetical order)! -->

- [@dan-frank](https://github.com/dan-frank)
- [@TWSOliverHill](https://github.com/TWSOliverHill)
