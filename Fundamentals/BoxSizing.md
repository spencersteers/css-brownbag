### Box Sizing

Two possible values for `box-sizing`

- `content-box`
    - The height and width of the element are measured by including **only the content**.


- `border-box`
    - The height and width of the element are measured by including **content, padding and border**.


### Example
<style>
.content-box {
    box-sizing: content-box!important;
    width: 600px;
    padding: 10px;
    background: #02b875;
    color: white;
}
.border-box {
    box-sizing: border-box;
    width: 600px;
    padding: 10px;
    background: #e368d6;
    color: white;
}
</style>

<div class="content-box">
.content-box
</div>
<br />
<div class="border-box">
.border-box
</div>

<br />

```html
<div class="content-box">.content-box</div>
<div class="border-box">.border-box</div>
```

```css
.content-box {
    box-sizing: content-box;
    width: 600px;
    padding: 10px;
}
.border-box {
    box-sizing: border-box;
    width: 600px;
    padding: 10px;
}
```
