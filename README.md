WebGL-2D
========

#### HTML5 Canvas2D API in WebGL. ####

**Author:** Corban Brook [@corban](http://twitter.com/corban)

This project aims to be a complete port of the Canvas2D API implemented in a WebGL context. 
It should allow _most_ Canvas2D applications to be switched to a WebGL context simply by including 
this lib and running a small initialization stub.

Switching your Canvas2D sketch to a WebGL2D sketch is very simple and only requires one line of code to change:

    var cvs = document.getElementById("myCanvas");

    WebGL2D.enable(cvs); // adds "webgl-2d" context to cvs

    var ctx = cvs.getContext("webgl-2d");

