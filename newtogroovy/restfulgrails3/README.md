# intro-grails3-gr8workshops

##Intro to Grails 3

An introduction to Grails talk adapted from previous Grails courses taught by Jenn.

# About the Slides

## Running Locally
This presentation is based on the [Object Partners Reveal Template](https://github.com/objectpartners/opi-reveal-template) which uses jade as a templating engine and grunt to run, reload, and publish the presentation to github pages.

* `npm install`
* `bower install`
* `grunt assemble`
* `grunt run`

Source code is in the *src* folder.  The distrubution is in the *dist* folder. Be careful. Changes in *dist* will be overwritten by the next assemble or reload.

## Publishing to github
Github supports web hosting on the gh-pages branch of a repository(like this one!)

If you have forked this repository, the `grunt publish` task takes the dist folder and packages it on the gh-pages branch of your repository. Remember to run `grunt assemble` before publishing.
