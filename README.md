# CRT Monitor CSS Filter for Neocities

A lightweight and simple CRT filter, made specifically for Neocities sites. 

Inspired by this [pure CSS CRT filter](http://aleclownes.com/2017/02/01/crt-display.html) by Alec Lownes. Use his filter for a better experience, use mine if you don't want your RAM to cry every time you load your site.

# To Install on your Neocites site:

Just drop the PNG image ("pixel.png", required) and CSS file into the main directory of your site and make a DIV on your site like this: 

```<crt id="crt"></crt>``` 

And declare the stylesheet in the ```<head>``` section like this:

```<link rel="preload" href="crt.css" as="style">```
  
```<link rel="stylesheet" href="crt.css">```

__DOES NOT WORK IN INTERNET EXPLORER!__ IE doesn't play nice with opacity percentages. I plan on fiddling with my own RGBA version like Alec's in the future that should work on IE, but for now just use his if you need that functionality.
