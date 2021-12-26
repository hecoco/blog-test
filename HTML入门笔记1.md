## HTMl发明者
英国计算机科学家、万维网发明者/主席/基金会创办人：蒂莫西·约翰·伯纳斯-李爵士(Sir Timothy John Berners-Lee)<br>
在1989年3月初步构想使用与ENQUIRE系统相似的概念创建万维网，在1990年底写出浏览器和服务器软件，并完成第一次通讯。为初代HTML。
</head>


## HTML起手式
```HTML
<!DOCTYPE html>===表示文本内容为HTML
<html lang="cn-ZH">===语言使用中文简体
<head>===头部/元数据
    <meta charset="UTF-8">===告诉浏览器使用“UTF-8”的编码格式
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>===网页标题
</head>
<body>===主体
</body>
</head>
</html>
```

## 常用章节标签

## 全局属性

## 常用内容标签



## 标签
style===一般是在head使用,CSS样式<br>


div
a
p
h1~h5
script

## 属性
hidden===隐藏标签<br>
contenteditable=====让内容可编辑;默认为false<br>
tabindex===tab键聚焦；从1开始，0是最后一个，-1是不要tab到我。可以是无序的<br>
title===鼠标悬浮显示内容<br>
margin===外边距<br>
padding===内边距<br>



## 样式选择器
class
id===不到万不得已不要用id,id是唯一的,多次使用不会报错
标签选择器


## 其他
```css
white-space: nowrap;
text-overflow: ellipsis;
overflow: hidden;
```
溢出换行最后改成省略号
