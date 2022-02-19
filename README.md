# CRT Monitor CSS Filter for Neocities

A lightweight and simple CRT filter, made specifically for Neocities sites. 

Inspired by this [pure CSS CRT filter](http://aleclownes.com/2017/02/01/crt-display.html) by Alec Lownes. Use his filter for a better experience, use mine if you don't want your RAM to cry every time you load your site.

>__To Install on your Neocites site:__

Just drop the PNG image ("pixel.png", required) and CSS file into the main directory of your site and make a DIV on your site like this: 

```<div id="crt"></div>``` .

>__Incompatibilites__

Uses ```mix-blend-mode: overlay;``` which sometimes has issues blending with any ```background-color``` set on the ```body``` tag directly. If this issue occurs, it can be solved with another DIV like this:

```<div class="span" style="background-color: INSERT YOUR COLOR HERE" ></div>```

Just place it at the bottom of your z-index and you should be good to go.
