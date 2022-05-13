# CRT Monitor CSS Filter for Neocities

A lightweight and simple CRT filter, made specifically for Neocities sites. Uses APNG file format for minimal RAM usage!

Inspired by this [pure CSS CRT filter](http://aleclownes.com/2017/02/01/crt-display.html) by Alec Lownes. Use his filter for a better experience, use mine if you don't want your RAM to cry every time you load your site.

# To Install on your Neocities site:

Just drop the __APNG__ image ("pixel.apng", required) and the __CSS__ file into the main directory of your site and make an element on your site like this: 

```<crt id="crt"></crt>``` 

And declare the stylesheet in the ```<head>``` section like this:

```<link rel="preload" href="crt.css" as="style">```
  
```<link rel="stylesheet" href="crt.css">```
