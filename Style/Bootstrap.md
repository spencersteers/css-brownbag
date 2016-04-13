### Overriding Bootstrap

Be **extremely** careful when doing this.

- Always make sure your overrides are scoped
- Never override bootstrap grids and columns
- If you use Bootstrap layout classes follow the documentation for them exactly

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

Let your class structure be your api.
