http-server

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
宽度等于设备的宽度 默认缩放比例一倍 最小缩放一倍 最大缩放一倍 不准缩放
    <title>Document</title>===网页标题
</head>
<body>===主体
</body>
</head>
</html>
```

## 常用章节标签
h1~h6  
section 章节 一般会包含一个h1~h6标签  
article  
main  
aside  

## 全局属性
class  
id  
contenteditable=====让内容可编辑;默认为false  
style 使用css属性  
tabindex===tab键聚焦；从1开始，0是最后一个，-1是不要tab到我。可以是无序的  
hidden===隐藏标签    

## 常用内容标签
a 超链接  
strong 加粗  
em 斜体 让用户着重阅读 可嵌套  
code 展示代码  
pre 内容的空格换行都可以展示 不需要用&nbsp br等  