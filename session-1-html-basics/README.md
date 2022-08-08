# BASIC HTML

## HTML Documents

All HTMl Documents start with a document type declaration --> `<!DOCTYPE html>`

To indicate where your HTML code starts (your "block" of code) start with a `<html>` and end with `</html>`

The visible part of the HTML document is between  `<body>` and `</body>`

A shortcut is to type "!" and press enter

## HTML Elements

HTML elements usually have an opening tag and a closing tag, and whatever is written between the two tags is rendered. 

These are headings tags, with `<h1>` being the largest and `<h6>` being the least:

```
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 1</h4>
<h5>This is heading 2</h5>
<h6>This is heading 3</h6>

<p>This is a paragraph tag</p>
<b>This is a bold tag</b>
<i>This is a bold tag</i>

```

Other common tags include the `<span>` and `<div>` tags. You can think of these as dividers within your website. 

**NEVER SKIP THE END TAG, OR ELSE YOUR CODE WILL NOT RENDER**

There are many single tags that do not need to use an end tag:

The `<a href = "">` tag defins a hyperlink, whatever is written within the source (`href`), you will be directed to that page when you click on the link.

the `<img src = "">` tag defines an image, whatever image is defined inside the `src` will be rendered.

the `src` can be either an online source (**use image address instead of image link**) or a directory to another file (see demo)

The <img> tag also contains the `width` and `height` attributes, which specifies the width and height of the image (in px). it also contains an `alt` tag, which is kind of like a backup title for when the image doesn't shows:

`<img src="some_file.jpg" width="500" height="600" alt = "some image">`

## Commenting

It is always a good idea of comment your code!

![alt text](https://memezila.com/saveimage/Code-comments-be-like-this-is-a-stop-sign-meme-1022)

## Class and ID


## Chrome Inspect

Most of the time, when developers sees something cool on a website, they can "borrow" the code

Right-click on an element, and choose "Inspect" or "Inspect Element" to see what elements are made up of.
