# Sketching with Code

This is a serious of tutorials on illustrating data and concepts with code.

## Getting started

Download and install Sublime Text <a href='https://www.sublimetext.com/3'>https://www.sublimetext.com/3</a>

or Visual Studio Code <a href='https://code.visualstudio.com/'>https://code.visualstudio.com/</a>  

I will be using Sublime Text <a href='https://www.sublimetext.com/3'>https://www.sublimetext.com/3</a> and Google Chrome   <a href='https://www.google.com/chrome/dr/download'>https://www.google.com/chrome/dr/download</a> in the Sketching with Code series.   

I will be using Mac OS X and its built-in command line terminal. If you are on Windows you will need to download a command line editor that runs bash.

The idea behind sketching on HTML is very simple.

1. We create a canvas

```html:

<canvas id="canvas" width="333" height="222" style="border:1px solid #000000;">
</canvas>

```

2. We draw things on that canvas with simple curves and lines using javascript.



```html:

<canvas id="canvas" width="333" height="222" style="border:1px solid #000000;">
</canvas>

<script>
var c = document.getElementById("canvas");
var ctx = c.getContext("2d");
ctx.beginPath();
ctx.arc(95, 50, 40, 0, 2 * Math.PI);
ctx.stroke();
</script>

```

In the Sketching with Code series we will start by drawing very simple things and increasingly get more complicated, add animation, add text, import data, etc. until we can visualize nearly any concept or data set with javascript and an HTML canvas.


## NPM and Node.js

The NPM – Node Package Manager is the default package manager for NodeJs. Basically, NodeJs is a JavaScript runtime environment, allowing developers to develop the scalable applications. 

Components of NPM

1) Website: You can find packages from the official NPM website for your project. Also, you can create and set up profiles to manage and access all types of packages.

2) Command Line Interface (CLI): To interface with NPM packages and repositories, the CLI runs from your computer's terminal.

3) Registry: It has a huge database of JavaScript projects and meta-data. Thus, it allows you to use any supported NPM registry. Also, you can utilize someone else’s registry as per their terms of use.

### Installing Node.js and NPM

To install Node.js and NPM go the the Node.js website <a href='https://nodejs.org/en/download/'>https://nodejs.org/en/download/</a>

### Check Node.js and NPM Version

To check Node.js and NPM Version open up your cammand prompt


To confirm Node installation, type node -v command.

To confirm NPM installation, type npm -v command.

```bash

> node -v

> npm -v 

```

### Update Your NPM Version
Node.js doesn’t automatically update the version of npm.

Write a given command and your npm version will be updated.


```bash


> sudo npm install npm --global


```

## Install canvas-sketch

```bash
# Install the CLI tool globally
> npm install canvas-sketch-cli -g

or
> sudo npm install canvas-sketch-cli -g

```

## Create a new sketch

```bash
# Scaffold a new 'sketch.js' file and open the browser
canvas-sketch SwC_Test.js --new --open
```

## Useful Links

HTML5 Canvas  <a href='https://www.w3schools.com/html/html5_canvas.asp'>https://www.w3schools.com/html/html5_canvas.asp</a>



