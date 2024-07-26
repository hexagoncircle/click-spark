# click-spark

Add a little spark to your clicks. ✨

<a href="https://codepen.io/hexagoncircle/full/bGZdWyw">CodePen demo</a>

## Usage

Add the custom element wherever we want to see sparks fly.

```html
<body>
  <!-- sparks appear everywhere we click -->
  <click-spark></click-spark>
</body>

<div class="container">
  <!-- sparks only appear when clicking inside container -->
  <click-spark></click-spark>
</div>
```

## Change spark color

Set a spark color via CSS custom property:

```html
<click-spark style="--click-spark-color: blue"></click-spark>
```
