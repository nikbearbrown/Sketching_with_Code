# Sketching with Code

c is a serious of tutorials on illustrating data and concepts with code.

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

## Useful Links

HTML4 Canvas  <a href='https://www.w3schools.com/html/html5_canvas.asp'>https://www.w3schools.com/html/html5_canvas.asp</a>



