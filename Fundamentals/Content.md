### Content

**Inline** elements have height determined by the `line-height` property

**Block** elements fill the **width** of their parent and will expand **height** to fit their children



### Example
#### Parent Block -> Child Block -> Child Inline
<style>
.parent {
    border: 2px dashed #333;
    height: 75px;
}
.child {
    background: #a0c5e8;
}
</style>

<div class="parent">
    <div class="child">
        <span>inline child</span>
    </div>
</div>

<br />

```html
<div class="parent">
    <div class="child">
        <span>inline child</span>
    </div>
</div>
```

```css
.parent {
    height: 75px;
    border: 2px dashed #333;
}
.child {
    background: #a0c5e8;
}
```
