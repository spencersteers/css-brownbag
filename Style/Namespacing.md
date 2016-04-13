### Adding Namespaces to our CSS

```html
<div class="component-name">
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
.component-name {
    .component-name-wrapper {
        ...
    }
    .component-name-header {
        ...
    }
    .component-name-content {
        ...
    }
    .component-name-title {
        ...
    }
    .component-name-input {
        ...
    }
}
```
