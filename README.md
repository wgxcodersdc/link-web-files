# Linking up Web Files
This is meant to be the simplest of examples for how you move on from something like [Codecademy](http://www.codecademy.com/)'s Javascript lesson to working with files on your computer. This doc covers some basics with a few examples but you should download the zip to see how they all work in tandem. At the [bottom there are exercises]() which you'll need the source files for anyway.

## Hooking up CSS
To link to a CSS file you use a ```link rel```. An example is below:

```html
	<link rel="stylesheet" href="css/main.css">
```

The important thing to notice here is that the link is _relative:_ this means that the files are within the current project folder. This is diferent from an [absolute link](), which you've probably also written. One thing you should never write is this:

```html
	<link rel="stylesheet" href="C://username/Documents/code/my-project/css/main.css">
```

This is linking to a file on your computer, which other people can't see when you upload your files to a web server. (Not to mention that the short link is a lot easier to read.)

## Hooking up Javascript


### Colophon
The ```index.html``` is a modified version of [HTML5 Boilerplate](http://html5boilerplate.com/), which is a pretty great way to start any project.

The images are from [@helenvholmes' Instagram](http://instagram.com/helenvholmes).