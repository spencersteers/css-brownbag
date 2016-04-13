### Make it easy to override

Try to only nest styles one level deep. Overrides then become very easy and predictable.

```html
<div class="component-name my-custom-theme">
    <div class="component-name-wrapper">
        <div class="component-name-header">
            <h1 class="component-name-title"></h1>
        </div>
        <div class="component-name-content">
            <input type="text" class="component-name-input">
        </div>
    </div>
</div>
```

```less
.my-custom-theme.component-name {
    .component-name-wrapper {
        border: 1px solid green;
    }
    .component-name-header {
        font-size: 16px;
        color: black;
    }
}
```
