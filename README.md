
# Conde Nast Tech Test - Option 1

## Setup
------------------------------------------
This setup require NPM to install packages so please ensure you have node and npm installed.

For the setup, clone the repo from Git and run:

```js
npm install
```

You may need to compile templates and styling before viewing the website. To build templates, run:

```js
node build.js
```

And to compile stylesheets, run:

```js
npm run build-sass
```

To start the server, run:

```js
./node_modules/nodemon/bin/nodemon.js app.js
```

The website should now be viewable at http://localhost:3000/


## About
------------------------------------------
For the sake of saving time and for convenience, I have put all the sass into one file.
The files should be separated in real life situations for better readability and manageability.
They can then be compiled and concatenated as necessary before release to production. 
 
e.g.    normalise.scss
        core-styles.scss
        page-layout.scss
        article.scss
        article-list.scss
        error.scss

I have also 


## Issues
------------------------------------------
In case of any issues with setup, the packages can be individaully installed:

```js
npm install express
npm install nodemon
npm install handlebars
npm install just-handlebars-helpers
npm install npm-sass
```
