### Absolute Position

Start by locating the problem elements and the parent establishing their context.

<style>
.container {
    background: whitesmoke;
    width: 100%;
    height: 150px;
    position: relative;
    overflow: scroll;
    margin-bottom: 20px;
}
.bar {
    background: #ffd119;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 50px;
}
.content {
    width: 100%;
    height: 100%;
    position: relative;
    top: 50px;
}
</style>


<div class="container">
    <div class="bar"></div>
    <div class="content">content</div>
</div>

```html
<div class="container">
    <div class="bar"></div>
    <div class="content"></div>
</div>
```
```css
.container {
    background: whitesmoke;
    width: 100%;
    height: 150px;
    position: relative;
    overflow: scroll;
}
.bar {
    background: #ffd119;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 50px;
}
.content {
    width: 100%;
    height: 100%;
    position: relative;
    top: 50px;
}
```
