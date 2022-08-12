# Flexbox (& Fonts)

![Meme](https://preview.redd.it/88ncpcish2n41.png?auto=webp&s=f643233259c663f0f55119753cfed87bbef33bd1)

## Fonts

Choosing the right font has a huge impact on how the readers experience a website.

In CSS there are five generic font families:

1. Serif fonts have a small stroke at the edges of each letter. They create a sense of formality and elegance.
2. Sans-serif fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.
3. Monospace fonts - here all the letters have the same fixed width. They create a mechanical look. 
4. Cursive fonts imitate human handwriting.
5. Fantasy fonts are decorative/playful fonts.

There's how you set a font:

```
p {
  font-family: "Times New Roman", Times, serif;
}
```

Or a custom font from [google font](https://fonts.google.com/):


```
p {
  font-family: font-family: 'Rubik Distressed', cursive;
}
```

Note: some fonts wont work with different browsers (that is why we always have a backup font).

## Flexbox

The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning.

To start using the Flexbox model, you need to first define a flex container.

```
.some-flexbox-container {
  display: flex;
}
```

The `flex-direction` property defines in which direction the container wants to stack the flex items.

<img src="https://css-tricks.com/wp-content/uploads/2018/10/flex-direction.svg" width="300" />

Setting `flex-wrap` to `wrap`, your elements gets pushed to the next row when your elements reach the container's border.

The `justify-content` property is used to align the flex items:

<img src="https://css-tricks.com/wp-content/uploads/2018/10/justify-content.svg" width="300" />

The `align-items` and `align-content` property are also used to align the flex items:

<img src="https://css-tricks.com/wp-content/uploads/2018/10/align-items.svg" width="300" />

<img src="https://css-tricks.com/wp-content/uploads/2018/10/align-content.svg" width="300" />

### Perfect Centering

Set both the `justify-content` and `align-items` properties to center, and the flex item will be perfectly centered:

```
.some-flex-container {
  display: flex;
  height: 300px;
  justify-content: center;
  align-items: center;
}
```
