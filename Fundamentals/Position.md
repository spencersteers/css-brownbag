### Position

`position` is used to change the normal flow of the page.

When an element is positioned on the page, the already placed elements influence the position of the next element.

All elements default to `position: static;`
<style>
.inline-blocks {
    margin-top: 20px;
    margin-bottom: 20px;
}
.inline-blocks div {
    display: inline-block;
    background: #00e1ff;
}
.blocks {
    margin-top: 20px;
}
.blocks div {
    background: #ffd119;
}
</style>

<div class="blocks">
    <div>block</div>
    <div>block</div>
</div>
<div class="inline-blocks">
    <div>inline-block</div>
    <div>inline-block</div>
    <div>inline-block</div>
</div>


`top`, `right`, `bottom`, `left` and `z-index` have no effect on statically positioned elements
