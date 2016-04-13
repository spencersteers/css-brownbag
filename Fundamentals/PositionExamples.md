### Position Examples

#### Bar with sections for left, right, and centered items


<style>
.bar {
    width: 100%;
    height: 50px;
    position: relative;
    background: whitesmoke;
    margin-bottom: 20px;
}
.left-items {
    background: #ffd119;
    position: absolute;
    height: 100%;
    width: 100px;

    top: 0;
    left: 0;
}
.right-items {
    background: #00e1ff;
    position: absolute;
    height: 100%;
    width: 100px;

    top: 0;
    right: 0;
}
.center-items {
    text-align: center;
    width: 100%;
    height: 100%;
}
</style>

<div class="bar">
    <div class="left-items">
        .left-items
    </div>
    <div class="center-items">
        .center-items
    </div>
    <div class="right-items">
        .right-items
    </div>
</div>


```html
<div class="bar">
    <div class="left-items">
        .left-items
    </div>
    <div class="center-items">
        .center-items
    </div>
    <div class="right-items">
        .right-items
    </div>
</div>
```

```css
.bar {
    width: 100%;
    height: 50px;
    position: relative;
}
.left-items {
    height: 100%;
    width: 100px;
    position: absolute;

    top: 0;
    left: 0;
}
.right-items {
    height: 100%;
    width: 100px;
    position: absolute;

    top: 0;
    right: 0;
}
.center-items {
    width: 100%;
    height: 100%;
    text-align: center;
}
```
