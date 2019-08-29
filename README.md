# HTML学习记录
 

#### *VS CODE快捷键简介*

**比较常用的快捷键**

| 快捷键 |说明 |
|-----|:----:|
|tab | 补全代码|
|Ctrl+N|创建新文件|
|Alt+B|浏览器中显示网页|
|!+回车|生成HTML模板|
其他的快捷键点击这里：[常用快捷键](https://blog.csdn.net/qq_39082182/article/details/82381304)

艹，他这个表格不能距离上面那个太近，艹 错了好久了

### HTML相关知识点

##### 转义字符

一些特殊字符需要特殊的符号来表示这些特殊字符，这些特殊字符我们称为实体（转义字符串）
markdown文档显示不了
了解具体转义字符请点击:[转义字符](https://blog.csdn.net/qq_27674439/article/details/93116914)
<br>
ps:  markdown中添加空格使用&nbsp；注意分号是英文

---
##### meta标签
 meta 标签还可以设置网页的关键字
 name值对content进行描述

    <meta name="keywords" content="html5，JavaScript，Java"/>

可以做请求的重定向
即是网页在五秒后跳转到百度界面
meta标签是写在head中的

     <meta http-equiv="refresh" content="秒数;url=目标路径"/>
     <meta http-equiv="refresh" content="5;url=http://www.baidu.com"/>

---
##### 内联框架
使用内联框架可以引入一个外部的页面
使用iframe来创建一个内联框架
属性：
&nbsp;&nbsp;src：只想一个外部界面的路径，可以使用相对路径

    <iframe src="xhtml标签.html"></iframe>


---
#### 超链接
使用超连接可以让我们从一个界面跳转到另一个界面
使用a标签来创建一个超链接
属性：
&nbsp;&nbsp;href:指向链接跳转的目标地址，可以写一个相对路径，也可以写一个完整的地址
&nbsp;&nbsp;target:规定在何处打开链接文档

    <a href="meta标签.html">meta标签</a>
    <a href="http://www.baidu.com" target="blank">百度</a>


---
