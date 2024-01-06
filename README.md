# click-spark

Add a little spark to your clicks. ✨

<a href="https://codepen.io/hexagoncircle/full/bGZdWyw">CodePen demo</a>

## Usage

Put the custom element before the closing `</body>` tag:

```html
<body>
  <!-- other page elements -->
  <click-spark></click-spark>
</body>
```

## Change spark color

Set a spark color via CSS custom property:

```html
<click-spark style="--click-spark-color: blue"></click-spark>
```

## Set active elements

Want the spark to only occur on particular elements? Pass in a comma-separated list of selectors:

```html
<click-spark active-on=".send-sparks, #i-love-sparks, [data-sparks]"></click-spark>
```

Here's a [CodePen demo](https://codepen.io/hexagoncircle/pen/rNReOPd) of that example.

## Dev notes

This is very experimental and created for the joy of the web. More testing should be done before deploying this one to prod.

PRs and feedback always welcome. 🎷
