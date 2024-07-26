# click-spark

Add a little spark to your clicks. ✨

[CodePen demo](https://codepen.io/hexagoncircle/full/bGZdWyw) | [Blog post](https://ryanmulligan.dev/blog/click-spark/)

## Usage

Add the custom element wherever we want to see sparks fly.

```html
<script type="module" src="click-spark.js"></script>

<body>
  <!-- only add sparks within this container -->
  <div class="container">
    <click-spark></click-spark>
  </div>

  <!-- sparks appear everywhere we click -->
  <click-spark></click-spark>
</body>
```

## Change spark color

Set a spark color via CSS custom property:

```html
<click-spark style="--click-spark-color: blue"></click-spark>
```
