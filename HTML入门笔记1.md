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



## 常用标签和属性
a 标签<br>
href    跳转网站使用 //google.com ，会自动跳转到使用的http协议
        #XXX    跳转到标记锚点并置顶
        伪协议：
            javascript:;    可以实现一个无效的a标签
            mailto:邮箱
            tee:号码
target  
    _blank  在新的窗口打开
    _top    在当前窗口的根级打开
    _parent 在当前窗口的父级打开
    _self   默认值；在当前窗口打开
rel=noopener


table>thead;tbody;tfoot>th;td   表格
    css:
        table-layout: auto;默认值；等分 fixed;智能平均
        border-collapse:collapse;合并单元格
        border-spacing:0;单元格间隔为0



img 标签
    alt 当img失效时显示
    width/height 宽高
    max-width:100% 响应式布局
    事件：
        onload 当图片加载成功执行
        onerror 当图片加载时发生错误执行(可以替换成404)


form 表单
    form里面的标签需要有name属性
    type="submit" 才能提交表单
    action：跳转到哪一个页面
    method：GIT默认；POST
    autocomplete：on用于用户名  off默认值
    target：与a标签相同

    onsubmit 当用户提交表单时触发


input type 属性
    test 文本款
    password 密码框
    gender/checkbox：单选/多选 同一组单选/多选需要添加相同name属性
    file 文件 默认是选择单个文件 multiple 可选择多个文件
    hidden 隐藏

    onchange 改变内容时触发
    onfocus 鼠标/光标获得焦点触发
    onblur  鼠标/光标失去焦点触发

iframe 标签

textarea 多行文本框 默认用户可以改变文本款大小 添加css属性 resize：none；
select>option 下拉列表框



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


```html
<input type="submit"/>
<button tupe="submit">提交<button>
input和button两个的区别？
button里面还可以写其他内容，而input不行；比如button可以用图片来表示，而input不行。
```


