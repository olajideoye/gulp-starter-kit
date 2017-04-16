# frontend-starter-kit
![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg) ![Dependencies](https://david-dm.org/olajideoye/frontend-starter-kit.svg)

A simple starter kit for front-end projects based on my experience as a front-end web developer. 

I've setup this starter kit based on the tools I currently use and love.


## What's this project about
This starter-kit is a way to document a standard approach for myself, and reduce time I spend to set up a new project. Here's what you'll get out of the box:

- An opinionated project folder structure (which can be easily reconfigured)
- A gulpfile full of useful functions for different tasks

While the list above is great, there are a few things I stayed out of intentionally:

- **A Node.js server**: I stayed out of including a Node.js server because I don't always need one on my projects
- **Gulp task functions for JavaScript**: I've found that my needs for JavaScript in a project varies widely, from writing simple ES5 files to Express.js apps to writing SPAs and bundling everything together with Webpack and Babel.js. I intend to add a few functions in the future to do things like linting, minification and transpiling code. 


## Setup
#### Install Node.js and NPM
If you don't have Node.js installed, please go ahead and grab it [here](https://nodejs.org/). NPM is the package manager for Node.js and comes bundled with Node.js

To confirm that you have Node.js installed, run the following in your terminal:
```bash
node -v
```
You should get something like `v6.9.1`.

To confirm that you have NPM installed, run the following in your terminal:
```bash
npm -v
```
You should get something like `3.10.9`.

#### Install Node.js Modules
```bash
npm install
```


## Next steps?
- Better documentation on folder structure and Gulp functions available
- Linting
- ES2015 support using Babel.js
- Bundling using Webpack


## License
This starter kit is licensed under the MIT license. You can grab it [here](https://github.com/olajideoye/frontend-starter-kit/blob/master/LICENSE)


## Credits
- Ọlájídé Oyè <olajide.oye@gmail.com>
