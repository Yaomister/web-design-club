# HTML 1


## What is HTML?

![Meme](https://i.imgflip.com/49j42o.jpg)

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

[Here's a List of all HTMl Tags](https://www.w3schools.com/tags/default.asp)

To display emojis, you must use their code from the UTF-8 alphabet (like ASCII code)

For example, 'A' is 65, and 😄 is 128516.

You would actually write it in html like `&#128516;`

[Here's a Complete List](https://unicode.org/emoji/charts/full-emoji-list.html)

## Commenting

It is always a good idea of comment your code!

`<!-- This is a comment -->`

The shortcut in VS code is to press `cmd "/"` over the block of code you want to comment out

Code with good commenting:

![Meme](https://wompampsupport.azureedge.net/fetchimage?siteId=7575&v=2&jpgQuality=100&width=700&url=https%3A%2F%2Fi.kym-cdn.com%2Fentries%2Ficons%2Fmobile%2F000%2F019%2F698%2F8RKAP94.jpg)

## Class and ID

The HTML `class`  and `id` attributes are used to specify a class and id for an HTML element.

A class name can be used by multiple HTML elements, while an id name must only be used by one HTML element within the page

The class attribute is often used to point to a class or id name in a style sheet. It can also be used by a JavaScript to access and manipulate elements with the specific class name.

To define a tag with a class and ID:

```
<div class = "some-class-name">     </div>
<span id = "some-id-name">     </span>

```

We will see applications of this very soon!

## Chrome Inspect

Most of the time, when developers sees something cool on a website, they can "borrow" the code

Right-click on an element, and choose "Inspect" or "Inspect Element" to see what elements are made up of.
