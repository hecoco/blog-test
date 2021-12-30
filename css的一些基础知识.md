[caniuse.com查看CSS是否支持某一个浏览器](https://www.caniuse.com)
### 语法
#### at语法
@charset "UTF-8";  
@import url(2.css);  
@media (min-width: 100px) and (max-width:200px){  
    
}

### 文档流
HTMl 5 中 不分内联和块级元素，所有的元素都可以是内联或块级元素，用display控制即可。  
display:   
inline 从左到右 到达最右边才会换行  
block 从上到下 每一个元素都会另起一行  
inline-block 有以上两个元素的特点 当最右边无法占满当前元素时会另起一行  

inline 宽度是由内部inline元素的和 不能指定width **不能在inline里面加 block 元素** 会发生无法解决的冲突  
block 默认自动计算宽度 不一定是100%（外边距内边距） 可以用width 指定  
**width 不要写100%**  

inline 高度是由line-height 行高 间接确定的（继承父级元素、字体等等） 跟height高度无关,  
block 元素的高度是由内部文档流的所有元素总和决定的，绝对定位不包含，也可以设置height  


overflow 溢出  
当内容大于容器的宽高时 内容内容会溢出  
overflow:auto 自动 大于时加滚动条，否则不加  
hidden 大于时隐藏  
visible 默认值 显示溢出的部分  
scroll 不论是否大于都显示滚动条  

脱离文档流的元素  
float  
position:absolute/fixed  
浮动是不是脱离了  文档流？？？？？  


## 盒模型  box-sizing
content-box 内容盒 width = 内容  
border-box 边框盒 width = 内容 + padding + border  

margin 外边距  
border 边框  
padding 内边距  
content内容  

兄弟相邻的两个margin会发生合并，且只发生在上下外边距，不会合并左右的外边距。**padding的上下不会合并。**
父子之间 在没有border的情况下margin 会与 padding 合并，加上border  overflow:hidden 溢出时隐藏 display:flex 都可以阻止合并

简单说一下盒模型
CSS的盒模型分两种：content-box和border-box，两个的区别是content-box的宽高是指的content，border-box的宽高是指的 边框 内边距 和 内容。

# border 调试大法  
# outline 调试大法  

