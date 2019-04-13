# CS52 Workshops:  STATIC SITE GENERATORS (JEKYLL)

![](https://media.giphy.com/media/5wWf7H89PisM6An8UAU/giphy.gif)

Brief motivation here as well as in presentation

## Overview

Summary of what we're about to do.

## Setup

### Windows

1) Install Chocolatey 
`@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin`

2) Close and reopen command prompt, remember to run it as administrator.

3) Install Ruby: `choco install ruby -y`

4) Repeat 2

5) Install Jekyll: `gem install jekyll`

### Mac 

1) In terminal, install Xcode command line tools: `xcode-select --install`

2) In terminal, agree to licences `sudo xcodebuild -license`

3) You should have homebrew by now so we're not going over that

4) Install Ruby `brew install ruby`

5) Install Jekyll `sudo gem install jekyll`

### Check Jekyll

* `jekyll -v`

## Step by Step

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
