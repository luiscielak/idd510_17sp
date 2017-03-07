# Project 4 - Grid Systems

In this project you will learn how to design and implement a grid system. The deliverable for this project consists on a modular responsive CSS grid that you will be able to reuse in future projects.

## Project: Grid Systems

1. Grid context
2. Columns
3. Gutters





**Resources:**

* [Don’t Overthink It Grids (CSS Tricks)][1]
* [Creating Your Own CSS Grid System][2]
* [A Complete Guide to Flexbox][3]



- - -

## 1. Grid context


**HTML**
```
<div class="grid">
  <!-- 100% wide -->
</div>
```

**CSS**


## 2. Columns

**HTML**
```
<div class="grid">
  <div class="col-2-3">
     Main Content
  </div>
  <div class="col-1-3">
     Sidebar
  </div>
</div>
```

**CSS**
```
[class*='col-'] {
  float: left;
}


.col-2-3 {
  width: 66.66%;
}
.col-1-3 {
  width: 33.33%;
}

// Clearing context
.grid:after {
  content: "";
  display: table;
  clear: both;
}
```

## 3. Gutters



```
*, *:after, *:before {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}



[class*='col-'] {
  padding-right: 20px;
}
[class*='col-']:last-of-type {
  padding-right: 0;
}

```



[1]: https://css-tricks.com/dont-overthink-it-grids/
[2]: http://j4n.co/blog/Creating-your-own-css-grid-system
[3]: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

















