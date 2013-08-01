# grid

---

//  Chopper 的栅格系统，布局专用，支持响应式。

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/grid.css">
<link type="text/css" rel="stylesheet" media="screen" href="src/responsive.css">
<link type="text/css" rel="stylesheet" media="screen" href="src/example.css">

注意：示例代码中.ex开头的class只做可视化文档的辅助作用，实际引用组件时不需要此类class。

### 常用法

````html
<div class="ui-grid-row-fluid">
    <div class="ui-grid-span11 ex-box">
        span11
    </div>
    <div class="ui-grid-span1 ex-box">
        span1
    </div>
</div>
<div class="ui-grid-row-fluid">
    <div class="ui-grid-span10 ex-box">
        span10
    </div>
    <div class="ui-grid-span2 ex-box">
        span2
    </div>
</div>
<div class="ui-grid-row-fluid">
    <div class="ui-grid-span9 ex-box">
        span9
    </div>
    <div class="ui-grid-span3 ex-box">
        span3
    </div>
</div>
<div class="ui-grid-row-fluid">
    <div class="ui-grid-span8 ex-box">
        span8
    </div>
    <div class="ui-grid-span4 ex-box">
        span4
    </div>
</div>
<div class="ui-grid-row-fluid">
    <div class="ui-grid-span7 ex-box">
        span7
    </div>
    <div class="ui-grid-span5 ex-box">
        span5
    </div>
</div>
<div class="ui-grid-row-fluid">
    <div class="ui-grid-span6 ex-box">
        span6
    </div>
    <div class="ui-grid-span6 ex-box">
        span6
    </div>
</div>
````

### 嵌套

````html
<div class="ui-grid-row-fluid">
    <div class="ui-grid-span9 ex-box">
        span9
    </div>
    <div class="ui-grid-span3 ex-box">
        span3
    </div>
</div>
<div class="ui-grid-row-fluid">
    <div class="ui-grid-span9">
        <div class="ui-grid-span9 ex-box">
            span9
        </div>
        <div class="ui-grid-span3 ex-box">
            span3
        </div>
    </div>
    <div class="ui-grid-span3">
        <div class="ui-grid-span8 ex-box">
            span8
        </div>
        <div class="ui-grid-span4 ex-box">
            span4
        </div>
    </div>
</div>
````
