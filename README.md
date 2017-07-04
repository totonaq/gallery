# Gallery Plugin
This is a simple jQuery plugin of responsive gallery.

## Install

Put the required stylesheet at the [top](https://developer.yahoo.com/performance/rules.html#css_top) of your markup:

```html
<link rel="stylesheet" href="[your path]/gallery.css" />
```

Put the script at the [bottom](https://developer.yahoo.com/performance/rules.html#js_bottom) of your markup right after jQuery:

```html
<script src="[your path]/jquery.js"></script>
<script src="[your path]/gallery.js"></script>
```

### Usage

Wrap your `img`'s with a container element (`div`). You can use the class name whatever you want:

```html
<div class="simple-gallery">
  <img src="[your path].[extension]">
  <img src="[your path].[extension]">
  <img src="[your path].[extension]">
  <img src="[your path].[extension]">
  <img src="[your path].[extension]">
  <img src="[your path].[extension]">
</div>
```

Call the [plugin](https://learn.jquery.com/plugins/) function and your gallery is ready.

```javascript
$(document).ready(function(){
  $('.simple-gallery').gallery();
});
```
