### Box Model

- **Content** has a few properties:
    - `width`, `min-width`, `max-width`, `height`, `min-height` and `max-height`
- **Padding** a few less:
    - `padding`
- **Margin**:
    - `margin`
- **Border**:
    - `border`

<style>
.content {
    background: #8bb5c0;
}
.content:before {
    content: 'content';
}

.padding {
    background: #c2cf8a;
}
.padding:before {
    content: 'padding';
}

.border {
    background: #fddd9b;
}
.border:before {
    content: 'border';
}

.margin {
    background: #f9cc9d;
}
.margin:before {
    content: 'margin';
}

.box-model {
    width: 300px;
    margin: 0 auto;
}
.box-model div {
    line-height: 30px;
    padding: 0 15px;
}
.box-model div:after {
    content: ' ';
    display: inline-block;
}
</style>


<div class="box-model">
    <div class="margin">
        <div class="border">
            <div class="padding">
                <div class="content" />
            </div>
        </div>
    </div>
</div>
