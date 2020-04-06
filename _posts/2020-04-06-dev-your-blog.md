---
layout: post
title: "Develop your own blog with Jekyll and Github!"
---

## 1.0 Install Jekyll

> Jekyll is a static website generator. You give it text written in your favorite markup language and it uses layouts to create a static. [^(1)]

In short, Jekyll is a software tool which alow you to easily create a website. Most static websites (doesn't require user interactivation) could be developed under Jekyll.

The easiest way to install Jekyll is thought Ruby-Devkit. Click [here](https://www.ruby-lang.org/en/downloads/) to download and install Ruby-Devkit on your local machine. 

1. Use default options for installation. Check if Ruby installed properly by goto @Jekyll_install_directory (`C:\Ruby26-x64\bin` by default for example), and run CMD command `ruby -v`.

2. At the last stage of the installation wizard, it's needed for installing gems with native extensions. gem installer could be involed automatically. Or manually by CMD command: `ridk install`. Press ENTER to install all extensions as default.

3. Open a new command prompt window at @Jekyll_install_directory. To install **jekyll**, run:

    `gem install jekyll bundler`.

4. Check if Jekyll installed properly: `jekyll -v`

## 1.1 Create a test site on local-machine

Browse to your desired directory, we're going to create a jekyll template site here:

1. Create new Jekyll template site:

    `jekyll new myblog`

2. Change into new directory

    `cd myblog`

3. Build the site and make it avaiable on local machine. (**Windows users:** run `chcp 65001` first to change the command prompt's character encoding to UTF-8 so Jekyll runs without errors.)

    `bundle exec jekyll serve`

4. Browse to site default address: http://locallhost:4000

## 1.2 Custom UI with Metro UI

MetroUI official website: http://a-g-f.github.io/metro-ui-jekyll/

## 2.1 Buy a domain



## Reference

[^(1)]: https://jekyllrb.com/docs/	"Jekyll Official Documentation"
