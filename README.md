# timreddick.me

Welcome to the repo for my personal website! Visit the published site at https://www.timreddick.me.

## Creating this Site

I created this site using Jekyll and the [Just the Docs](https://just-the-docs.github.io/just-the-docs/) template. It uses GitHub Actions to build and deploy to GitHub Pages. The first site I built with this template can be found here: https://www.timreddick.me/fcc-fastapi. I learned a lot about how to build Jekyll sites and how this particular template deploys during that process, so I decided to also use it for my personal website. Even though it's a documentation theme, I think it works pretty well here. I added a big, bold logo to the home page, which I think makes it feel a little less like technical documention when you land.

## Building the site locally

### Install prerequisites
To build this site locally, you need Ruby, Bundler, and Jekyll installed. I followed the [Jekyll Quickstart](https://jekyllrb.com/docs/) and [Jekyll Installation docs](https://jekyllrb.com/docs/installation//). On macOS, use Homebrew to install Ruby and Bundler. After installing Ruby, you can install Jekyll via a RubyGem. [RubyGems.org](https://rubygems.org/) is the package manager for distributing Ruby programs.

### Build the site
After cloning the repo to your local machine, navigate to the docs directory and run:

    bundler exec jekyll build

Bundler will install all the requirements as specified in the Gemfile and build the site in the `_site` directory.

### Serve the site

To run the site on a local web server, run:

    bundler exec jekyll serve

This will use the appropriate version of Jekyll and dependencies as specified in the Gemfile to serve the site. The link to the local server will be output to the command line. When you make changes to the site files, you will see those changes reflected on your site after reloading the page. However, if you change the `_config.yml` file, you will need to restart the server for those changes to take effect.

## Blog Post

I plan to write a blog post about my experience creating my first Jekyll sites, and in particular, I want to explain some of the customizations I made to the build and deployment process and some of the configurations I made to the theme. I also want to explore some alternative deployment patterns. I'll make this post to my personal website, and I'll add the link here when I do!