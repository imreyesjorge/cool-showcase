![](src/assets/docs/header.webp)

# Cool Showcase

This is a fresh, simple and cool showcase portfolio. It's free for anyone to fork-it and use it.

## How-to use it

This project is built with `pug`, `sass` and `parcel.js`.

> Also, you require `node.js` and `npm`. You can [download](https://nodejs.org/en/) both in the node.js webpage.

The directory structure of this project is this:

`docs` - The ready-to-use page is stored in here.
`src` - Here is all the source code (This is the directory you want to modify).
`src/styles` - All the `.scss` files goes here.
`src/index.pug` - In this file you can edit the display **name**, **badge**, and **social media** links.
`src/layout/head.pug` - This is where you can modify all the meta-data (`<head>` information).
`src/layout/main.pug` - Finally, in this file you can edit the projects you want to be in your showcase.

If you want to see the changes in real-time you can easily just run the `start` script.

#### For `npm` users:

```bash
npm run start
```

#### For `yarn` users:

```bash
yarn start
```

### How-to add a new project

Adding a new project is pretty simple, just add a new js block that looks something like this to the array.

```js
{
    name: 'Your-project-name',
    desc: 'Your-project-description',
    img: 'path/to/your/project/image',
    link: 'https://link-to-your-project.com'
}
```

### Time to build

When all the desired changes are made, we'll need to build the page so it's ready for deployment.

#### For `npm` users:

```bash
npm run build
```

#### For `yarn` users:

```bash
yarn build
```

This will run the `build` script in `package.json` and build the page in the `docs/` directory.

There's where your ready-to-use page is stored.

> You need to upload only the `docs/` directory to the server hosting your webpage.