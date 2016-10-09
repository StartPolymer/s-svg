# &lt;s-svg&gt;

A polymer element allowing SVG images to be responsive and styled with CSS.

## Using

Use optimized SVG. In Inkscape choose `Optimized SVG` file type upon `Save As` (Ctrl + Shift + S).

```xml
<svg height="50" viewBox="0 0 100 50" width="100" xmlns="http://www.w3.org/2000/svg">
...
</svg>
```

```css
.container {
  color: #fff;
  height: 200px;
}

.logo {
  fill: currentColor;
}
```

```html
<div class="container">

<s-svg class="logo" src="logo.svg" width="100" height="50"></s-svg>

</div>
```

## Install

`bower i s-svg -S`
