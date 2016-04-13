### Position Relative

When an element is `relative`, the page flows as if the element were static - and then the element is adjusted.

<style>
.position-relative-example .normal {
    width: 150px;
    height: 150px;
    display: inline-block;
    background: #f9cc9d;
}
.position-relative-example .relative {
    background: #a0c5e8;
    width: 150px;
    height: 150px;
    display: inline-block;
    position: relative;
    top: 10px;
    left: 10px;
}
</style>

<div class="position-relative-example">
    <div class="normal">normal</div>
    <div class="relative">relative</div>
    <div class="normal">normal</div>
    <div class="normal">normal</div>
</div>

<br>
```html
<div class="normal">normal</div>
<div class="relative">relative</div>
<div class="normal">normal</div>
<div class="normal">normal</div>
```

```css
.normal {
    width: 150px;
    height: 150px;
    display: inline-block;
}
.relative {
    width: 150px;
    height: 150px;
    display: inline-block;
    position: relative;
    top: 10px;
    left: 10px;
}
```
