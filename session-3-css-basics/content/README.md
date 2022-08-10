# CSS 1

## What is CSS?

CSS stands for Cascading Style Sheets

It describes how HTML elements are to be displayed on screen

Think if HTML as the bone and muscles of your body, while CSS is the skin, hair, clothing, etc. 

Here's a visual representation:

![Meme](https://preview.redd.it/s6vg7m59y9041.jpg?width=960&crop=smart&auto=webp&s=fcb732cbfc4318bb77113af1b7bb803165665c2d)

## How Do We Link HTML and CSS Files

In the heading section of your HTML file, you need to add the following tag:

```
 <link rel="stylesheet" href="styles.css">

```

The href should be a local path to your CSS file.

## CSS Syntax

The following is the general syntax:

```
selector{

  property : value ;
  property : value;

}

```

Example

```
p {
  color: red;
  text-align: center;
}

```

When you make the selector an element type, every element of that type will be affected by the style.

if you want to reference a class --> `.class-name`

if you want to reference an ID --> `#id-name`

if you want to select all elements --> `*`

if you want to select multiple ements at once --> `h1, h2, h3`


Remember,  one HTML element can have multiple classes and/or IDs.


## Common Attributes

These are some common ones:

`background-color`, `border-color`, `text-color`, you can assign a color

`background-image`, you can assign a background image

`border-style`, the following values are allowed, `dotted`, `dashed`, `solid`, `double`, `inset`, `outset`, `groove`, `hidden`

`text-alignment`, the following values are allowed, `center`, `left`, `right`

`border-width`, set the border line to a specific width

`margin`, set the top, left, right, bottom margin to a specific length (see margin explained below)

`padding`, set the top, left, right, bottom padding to a specific length (see padding explained below)

`width`, `height`, set the width and/or height of an element to a specific size (or percentage based on parent element)

Here's a full [list](https://www.w3schools.com/cssref/default.asp) of attributes

## Margin, Padding

A margin is the space around an element's border

padding is the space between an element's border and the element's content

![Difference](https://blog.hubspot.com/hs-fs/hubfs/Google%20Drive%20Integration/Update%20css%20margin%20vs%20padding-2.png?width=650&name=Update%20css%20margin%20vs%20padding-2.png)

## em, rem, px

When we use px, we are hardcoding how many pixels we want our element to take up.

However, it is better to use em and rem

rems and ems are relative units. for example, the default root font-size is 16 pixels, so 1 rem and 1 em are both 16px.

However, if the element is within an element that has a font-size of 32 pixels, 1 rem is still 16 pixels, while 1 em is 32 pixels.

We can change the root font-size like this

```
:root {
  font-size: 20px;
}
```

now 1 rem is 20px instead of 16


## Colors

There are many ways of representing color in CSS, with HEX and RGB being the most common.


RGB(Red-Green-Blue) is the process by which colors are rendered onscreen by using combinations of red, green and blue.

White's RGB would be 255,255,255, and Black would be 0,0,0, and every color would be between those numbers

HEX color is expressed as a six-digit combination of numbers and letters defined by its mix of red, green and blue (RGB). Basically, a HEX color code is shorthand for its RGB values with a little conversion gymnastics in between.


White's HEX is #ffffff, and Black would be #000000

You can search up "color picker" on google, and it will show you the color in both HEX and RGB

