## 步骤
子元素加float:left和width
在父元素加 .clearfix
```css
.clearfix::after{
    content:'';
    display: block;
    clear: both;
}
```

需要平均布局时  可以在布局中间加一个x元素 给定margin 为负数

![平均布局](img/平均布局时.jpg)








