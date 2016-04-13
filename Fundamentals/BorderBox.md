### Border Box Everywhere

Almost every css framework adds `box-sizing: border-box` to every element.

If you're using bootstrap, you're using `border-box`.

```css
*,
*:before,
*:after {
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
}
```

### Example

<style>
.parent {
    width: 600px;
    margin: 0 auto;
    border: 5px dashed #333;
}
.content-box {
    box-sizing: content-box!important;
    width: 100%;
    padding: 10px;
    background: #02b875;
    color: white;
}
.border-box {
    box-sizing: border-box;
    width: 100%;
    padding: 10px;
    background: #e368d6;
    color: white;
}
</style>

<div class="parent">
    <div class="content-box">.content-box</div>
    <br />
    <div class="border-box">.border-box</div>
</div>

<br />

```html
<div class="parent">
    <div class="content-box">.content-box</div>
    <div class="border-box">.border-box</div>
</div>
```

```css
.parent {
    width: 600px;
    margin: 0 auto;
    border: 5px dashed #333;
}
.content-box {
    box-sizing: content-box;
    width: 100%;
    padding: 10px;
}
.border-box {
    box-sizing: border-box;
    width: 100%;
    padding: 10px;
}
```
