### Position Absolute

When an element is `absolute` it is also said to be **absolutely positioned**.

Behaves much like `fixed` but is relative to the nearest positioned ancestor.

<style>
.absolute {
    width: 200px;
    background: #da3b01;
    color: white;
    position: absolute;
}
.spacer {
    padding-bottom: 100vh;
}
</style>

<div class="absolute">absolute</div>
<div class="spacer" />

```css
.absolute {
    position: absolute;
}
```
