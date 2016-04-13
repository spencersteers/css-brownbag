### No Element Left Behind

When making components provide an easy way to select all the elements.

```html
<div class="component-name">
    <div>
        <div>
            <div class="component-name-wrapper">...</div>
        </div>
    </div>
</div>
```

The two divs without classes will quickly become liabilities if they are given styles

```css
.component-name > div {
    width: 80%;
}
.component-name div {
    background: whitesmoke;
}
```

Your class structure becomes your documentation and is easy to reason and work with.
