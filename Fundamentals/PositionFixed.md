### Position Fixed

When an element is `fixed` it is said to be **absolutely positioned**.

Absolutely positioned elements are removed from the flow of the page and their original space is ignored.

The position of a fixed element is relative to the screen.

<style>
.fixed {
    width: 200px;
    background: #da3b01;
    color: white;
    position: fixed;
}
.spacer {
    padding-bottom: 100vh;
}
</style>

<div class="fixed">fixed</div>
<div class="spacer" />

```css
.fixed {
    position: fixed;
}
```
