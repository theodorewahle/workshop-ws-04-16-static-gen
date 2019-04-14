# CS52 Workshops:  STATIC SITE GENERATORS (JEKYLL)

![](https://media.giphy.com/media/5wWf7H89PisM6An8UAU/giphy.gif)

Static site generators allow the entire site to be built at one time on your computer before being put on the server. Static sites respond to requests much faster than dynamic ones, provide improved security since there's nothing dynamic to be exploited, and is better suited at handling traffic surges since it only needs to serve static files. Static sites can be a great solution if your information doesn't need to be constantly updated.

## Overview

Summary of what we're about to do.

## Setup

### Windows

1. Install a [Ruby+Devkit](https://rubyinstaller.org/) version . Use default options for installation.
2. Open a new command prompt window from the start menu, so that changes to the PATH environment variable becomes effective.
3. Install Jekyll and Bundler via: gem install jekyll bundler

### Mac 

1. In terminal, install Xcode command line tools: `xcode-select --install`

2. In terminal, agree to licences `sudo xcodebuild -license`

3. You should have homebrew by now so we're not going over that

4. Install Ruby `brew install ruby`

5. Install Jekyll `sudo gem install jekyll`

### Check Jekyll

* `jekyll -v`

## Step by Step

* Try a fully set-up jekyll template 
* In terminal/git bash `cd` into your preferred directory
* `jekyll new tester`
* `cd tester`
* `jekyll serve`
* Voila! You have a basic jekyll site you can tweak
![](img/Capture.png)


1. Create a site
  * Create a new directory for your site and name it whatever you'd like. Don't forget to initialize a Git repository.
  * Add your first file. Make an `index.html` file and add in the following code:
```<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Home</title>
  </head>
  <body>
    <h1>Hello World!</h1>
  </body>
</html> 
```
2. Build the site
    * We need Jekll to build the site before we can view it. To do this, we can run two commands:
        * `jekll build` - This will build our static site to a directory called `_site`.
        * `jekll serve` - Does the same thing except it will rebuild any time you change the site and will run a local server at `http://localhost:4000`.
    * While developing the site it's better to use `jekyll serve` as it updates with any changes you make.
    * Go ahead and run `jekyll serve` and go to `http://localhost:4000` in your browser. You should see "Hello World!".
Remember to explain any notation you are using.

```javascript
/* and use code blocks for any code! */
```

![screen shots are helpful](img/screenshot.png)

:sunglasses: GitHub markdown files [support emoji notation](http://www.emoji-cheat-sheet.com/)

Here's a resource for [github markdown](https://guides.github.com/features/mastering-markdown/).


## Summary / What you Learned

* [ ] can be checkboxes

## Reflection

*2 questions for the workshop participants to answer (very short answer) when they submit the workshop. These should try to get at something core to the workshop, the what and the why.*

* [ ] 2 reflection questions
* [ ] 2 reflection questions


## Resources

* https://learn.cloudcannon.com/jekyll-setup/
* 
