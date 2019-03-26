<!-- ![Adalab](_src/assets/images/logo-adalab-80px.png) -->

![siscode](_src/assets/images/siscode-black.png)

We are SISCODE and this is our first group project made in Adalab.
We coded an informative web page about us as a team and individually.
We used HTML, SCSS and Gulp.
You can contact us through the form on the page.

## Quick Start Guide

You will need to install [Node.js](https://nodejs.org/) and [Gulp](https://gulpjs.com) to work with this Repo, then:

1. Download or clone the repository.
2. Install local dependencies with `$ npm install`.
3. Start the web server with `$ gulp` to see the website and make changes as you wish.

## Gulp tasks included in this project

### Start a web server for development

```
$ gulp
```

This tast will launch a webserver with BrowserSync and several watchers will be watching the files SCSS / JS / HTML, in the folder **public/**, to reload the browser when needed.

### Final version to upload to production

```
$ gulp docs
```

This task will create a folder **docs/**, generates the CSS and JS minimized and without sourcemaps, ready to upload to the repo. Then you need to activate GitHub Pages in `master/docs`, and you could see your website in the URL provided.

## Structure of the project

The folder structure looks like this:

```
/
`- _src
   |- assets
   |  |- icons
   |  |- images
   |  |- js
   |  `- scss
   |     `- components
   |     `- core
   |     `- layout
   |     `- pages
   |
   `- templates
      `- partials

```

## HTML

It includes the package [**gulp-html-partial**](https://www.npmjs.com/package/gulp-html-partial) that will allow you to have an html templates/partials system.

## Images and Icons

You have in **\_src/** a folder for the images of the project and one for the icons like the favicon or the icons of mobile devices. The latter are generated in the root of the folders **public/** and **docs/**.

## CSS

In the project I used the package [**gulp-combine-mq**](https://www.npmjs.com/package/gulp-combine-mq) that groups all the mediaqueries at the end of the css document.

## Something is missing?

If you want to contribute to the project, change something that is not working properly or, you would like to offer a new feature, you can open a new issue.

Thank you for your interest in our project ❤︎.
