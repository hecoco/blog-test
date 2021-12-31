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

## 平均布局
在布局中间加X元素，margin-right的值为容器内容的负margin-right


最后一个items的margin会超出容器的宽度，跑到新的一行去了。  
方法：给容器一个子元素X，设置margin-right为-margin。  
items多出margin个像素，X元素margin为负数，**margin合并原则**。  

![平均布局](img/平均布局时.jpg)