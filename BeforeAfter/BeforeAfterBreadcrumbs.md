### Moving javascript logic into css

<style>
.breadcrumb {
    display: inline-block;
    margin: 15px;
    position: relative;
}
.breadcrumb:not(:last-child):after {
    content: '>';
    position: absolute;
    right: -20px;
}
</style>

<div>
<div class="breadcrumb">Crumb 1</div>
</div>

<div>
<div class="breadcrumb">Crumb 1</div>
<div class="breadcrumb">Crumb 2</div>
</div>

<div>
<div class="breadcrumb">Crumb 1</div>
<div class="breadcrumb">Crumb 2</div>
<div class="breadcrumb">Crumb 3</div>
</div>


```html
<div>
    <div class="breadcrumb">Crumb 1</div>
    <div class="breadcrumb">Crumb 2</div>
    <div class="breadcrumb">Crumb 3</div>
</div>
```

```css
.breadcrumb {
    display: inline-block;
    margin: 15px;
    position: relative;
}
.breadcrumb:not(:last-child):after {
    content: '>';
    position: absolute;
    right: -20px;
}
```
