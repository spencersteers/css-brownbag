### Display
#### inline-block
- Initial height and width like an inline element
- Behaves how a block element does in regards to the box model properties
    - `width`, `height`, `max-height`, `padding` ect


#### Example
<style>
.inline-blocks div {
    display: inline-block;
    background: #00e1ff;
}
.blocks div {
    background: #ffd119;
}
.inlines span {
    background: #00f076;
}
</style>

<div class="blocks">
    <div>block</div>
    <div>block</div>
</div>
<br />
<div class="inline-blocks">
    <div>inline-block</div>
    <div>inline-block</div>
    <div>inline-block</div>
</div>
<br />
<div class="inlines">
    <span>inline</span>
    <span>inline</span>
</div>
