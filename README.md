# Docsify JS Tutorial
> Tutorial on how to build a docs site with _Docsify-JS_ and _Github Pages_

[![Made with latest Docsify](https://img.shields.io/npm/v/docsify?label=docsify)](https://docsify.js.org/)
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/docsify-js-tutorial.svg)](https://GitHub.com/MichaelCurrin/docsify-js-tutorial/tags/)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](#license)


## 👩‍🏫 Follow the online tutorial

The [Docsify](https://docsify.js.org/#/) site does have a great quickstart, but then it lets you figure what to add next.

So this project was created as a more directed guide to take you through site setup and configuration, covering common usecases. It also assumes you already have a docs directory in a project and you want to turn it into a docs site. The tutorial gives you some tips and pitfalls to avoid, based on the author's experience. 

[![Docsify JS Template site](https://img.shields.io/badge/site-Docsify_JS_Tutorial-green?style=for-the-badge)](https://michaelcurrin.github.io/docsify-js-tutorial/#/)

This project's own site is built on _Docsify-JS_ so serves as a good example. That serves from the `docs` directory. There is no main application to separate from `docs` directory, so serving from that directory is just convenient.

See also the [Nested Example](/nested_example/README.md) section on the repo for understanding links in markdown and the sidebar.


## 🖨️ Use a template

If want to skip the tutorial and want a base project which has some sample data then go here:

[![Docsify JS Template site](https://img.shields.io/badge/site-Docsify_JS_Template-green?style=for-the-badge)](https://michaelcurrin.github.io/docsify-js-template/#/)

That is template repo which accompanies this tutorial repo. Click _Use this template_ button and follow the instructions in the README.md doc.


## 🎯 Project aims

Some background on how I arrived at DocsifyJS as a docs site builder.

My aims for building a docs site are:

- add as little code and configuration as possible
- make it easy to maintain
- quick to get setup on existing projects
- have no layout files
- reduce dependencies

The docs site tool used here is [Docsify-JS](https://docsify.js.org/) which is a frontend JS library written in VueJS. But if you have never used before or never coded in JS before, you'll be guided through. The only JS you need to write in your config values. You also need to edit some HTML values and possibly write a YAML file for your navbar, which again is more configuration than code.

This project's tutorial covers the basics and provides minimal setup instructions. You can add the quickstart project to your **existing** docs folder. If you doc files are markdown files, you don't have to rename them and their formatting can mostly stay the same i.e. no frontmatter or special syntax and the pages still render well as plain markdown even. But some links may need updating since `/docs` folder is now the root of the app.

Unlike static site builders like Jekyll or Hugo, you do **not** need to install or run a site generator or change the formatting or metadata of your markdown files. Your also don't need any separate config file - the configuration is handled in the _index.html_ page, which is also where dependencies are fetched in the browser and where the app starts.

_Docsify_ works as a single-page application on this one page - data from your markdown files is pulled in and displayed within the _Docsify_ UI shell. There are no template layout files to manage and you can choose from some themes easily without things breaking like when you switch themes in other static site generators.


## Contributing

The repo is open for accepting contributions through a Pull Request.

## License

Licensed under [MIT license](/LICENSE)

- You can modify and reuse this project.
- A copy of the license and copyright notice must be included with the software. [source](https://choosealicense.com/licenses/#mit).
- Please link back to this repo somewhere in your project.
