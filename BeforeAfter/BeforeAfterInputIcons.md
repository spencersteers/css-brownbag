### Elements with less boilerplate

<style>
.search {
    width: 200px;
    position: relative;
    margin-bottom: 20px;
}
.search input[type="search"] {
    box-sizing: border-box;
    color: #bbb;
    background: #efefef;
    font-size: 13px;
    width: 100%;
    height: 34px;
    padding: 6px 24px 6px 12px;
    line-height: 1.42857;
    border-radius: 4px;
    border: 2px solid #efefef;
    position: relative;
}

.search::after {
    content: " ";
    display: inline-block;
    position: absolute;
    right: 0;
    top: 0;
    width: 10px;
    height: 9px;
    margin-right: 12px;
    margin-top: 12.5px;
    margin-bottom: 12.5px;
    background-image: url(https://collaborate.reachengine.com/img/filter_icon.svg);
    background-size: 10px 9px;
    background-repeat: no-repeat;
}
</style>

<div class="search">
    <input type="search" placeholder="Search">
</div>


```html
<div class="search">
    <input type="search" placeholder="Search">
</div>
```

```css
.search {
    width: 200px;
    position: relative;
    margin-bottom: 20px;
}
.search input[type="search"] {
    box-sizing: border-box;
    color: #bbb;
    background: #efefef;
    font-size: 13px;
    width: 100%;
    height: 34px;
    padding: 6px 24px 6px 12px;
    line-height: 1.42857;
    border-radius: 4px;
    border: 2px solid #efefef;
    position: relative;
}
.search::after {
    content: " ";
    display: inline-block;
    position: absolute;
    right: 0;
    top: 0;
    width: 10px;
    height: 9px;
    margin-right: 12px;
    margin-top: 12.5px;
    margin-bottom: 12.5px;
    background-image: url(https://collaborate.reachengine.com/img/filter_icon.svg);
    background-size: 10px 9px;
    background-repeat: no-repeat;
}
```
