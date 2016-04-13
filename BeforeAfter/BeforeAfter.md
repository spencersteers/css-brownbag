### Cosmetic Styles

<style>
.list {
    margin: 0!important;
    padding: 20px!important;
    background: #2f2f2f;
    width: 300px;
    list-style: none;
    margin-bottom: 20px!important;
}
.list li {
    color: white;
    display: block;
    position: relative;
    cursor: pointer;
}
.list li.active:before {
    content: ' ';
    position: absolute;
    height: 100%;
    width: 2px;
    left: -20px;
    display: inline-block;
    background: #00aeef;
}
</style>


<ul class="list">
    <li>item 1</li>
    <li>item 2</li>
    <li>item 3</li>
</ul>



<script>
var list = document.querySelector('.list');
list.addEventListener('click', function(ev) {
  if(ev.target.tagName === 'LI') {
     ev.target.classList.toggle('active');
  }
}, false);
</script>


```html
<ul class="list">
    <li>item 1</li>
    <li>item 2</li>
    <li>item 3</li>
</ul>
```

```css
li {
    position: relative;
    display: block;
}
li.active::before {
    content: ' ';
    position: absolute;
    height: 100%;
    width: 2px;
    left: -20px;
    display: inline-block;
    background: #00aeef;
}
```
