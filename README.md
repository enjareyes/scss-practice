

# Course outline and slides
* [View course outline here](https://mike.works/course/sass-fundamentals-5438fec/stage/sass-fundamentals-ca61dca)
* [View slides here](https://docs.mike.works/sass-fundamentals)

# What are the pieces?

* [node-sass-middleware](https://github.com/sass/node-sass-middleware) for Sass compilation
* [express](http://expressjs.com/) for serving HTML and CSS (compiled from Sass)
* [commander](https://github.com/tj/commander.js) as a foundation for a CLI to run exerises
* [A little CSS testing framework](https://github.com/mike-works/sass-fundamentals/blob/master/public/js/tester.js) for asserting that exercise goals have been reached!

# Getting Set Up

There are a few things you need to ensure you have installed, in order to be ready for this course.

### Node.js

You’ll need a relatively recent version (v4.5 or newer, v7 ideally) of node.js installed. On OS X, a great way of doing this without disturbing your existing dev environment is to install NVM. [Installation instructions are here](https://github.com/creationix/nvm#installation).

You’ll know everything is set up properly when you can run

```
nvm --version # might look like "0.31.4"
node --version # might look like "v7.7.3"
```

### Visual Studio Code

Particularly if you’ve never tried it before, you should install [Microsoft Visual Studio Code](https://code.visualstudio.com/). Some fantastic extensions that I use regularly include
* [css-triggers](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.csstriggers)
* [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons)
* [Sublime Text Keymap](https://marketplace.visualstudio.com/items?itemName=ms-vscode.sublime-keybindings) - Install if you’re used to sublime text keyboard shortcuts

### Check out and setup the project for this workshop

```
git clone git@github.com:mike-works/sass-fundamentals.git
cd sass-fundamentals
npm install
```


# How to use it
Use the `run` command to launch an exercise

```sh
./run --exercise <exercise name>
```


