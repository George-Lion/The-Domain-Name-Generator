## The domain name generator

When creating a website, one of the fundamental parts is the domain, this will be the address, it is the key that unites your content with the user. The Domain Name Generator is designed with the aim of offering various alternatives to be chosen by the user.

The languages ​​used are HTML5 that will form the structure of our website, a css file that is responsible for the visual part and a JavaScript file where all the parameters that generate the process of the requested action are found.

The main part of the code is found in the js file, which is what shapes the entire process of selecting the domain name, within a function we have variables that have parts of sentences as their value that will make up the final domain name, these are looped through so that in each repetitive iteration they select one of the words that concatenate the final domain name.

Concepts applied in architecture:

* Use of Functions.
* Array implementation.
* Loops.
* Basic HTML structure.
 
Recommended websites for theme icons, images and tools:

[-Google Fonts Pages](https://fonts.google.com/).

[-Fontawesome Pages](https://fontawesome.com/).

[-Pexel Pages](https://www.pexels.com/es-es/).

# Hello World with Vanilla JS

Start coding in 30 seconds by opening this template in gitpod:
[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io#https://github.com/4GeeksAcademy/vanillajs-hello.git)

### Manual Installation

1) Remember to install the npm packages first:
```
$ npm install
```

2) Build and Start coding!

Build the application for the first time...

```
$ npm run start
```

And start coding your Vanilla.js application, update the `src/index.html`, `src/index.css` or `src/app.js` depending on your needs.

## FAQ

#### 1) How do I run my code?

- Type on the command line `$ npm run start` and type localhost on the browser.

#### 2) Where do I write my code?
It depends on the language, but you have `./src/js/app.js`, `./src/style/index.css` and `./isrc/index.html` respectively, you can add new `.html` as you please, just make sure to include import it on the index.js.

__Note:__ remember that the JS workflow starts inside `window.onload`.

#### 3) I don't see my changes.

Everytime you change any file inside the `./src` folder the website public URL will automatically refresh the changes (it's a process called hot deploy)
Remember also to refresh cleaning the cache (command+shift+r on mac, control+shift+r on pc & linux)

#### 4) How do I include more images on my project?
Add them inside the `./src/assets/img` folder and import them from any of your JS files. E.g: `import "../assets/img/rigo-baby.jpg";`

#### 5) How do I include more JS files?
Just add the files into the JS folder and import the file/variables into your index.js. E.g: `import myVar from "./file2.js"`

#### 6) How do I publish the website?

This boilerplate is 100% compatible with the free github pages hosting. Publish your website by running:
```sh
$ npm run deploy
```

Very easy and in just one step!  Push to your __master__ branch and use the free hosting that comes with [GitHub pages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/#enabling-github-pages-to-publish-your-site-from-master-or-gh-pages), the project is ready to be published. Remember to choose to run the Github Page from your master branch.
