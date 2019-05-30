**HTML：HyperText Markup language 超文本 标签 语言**



**一般的网页结构：**

<!DOCTYPE html>   --->声明:它是指示 web 浏览器关于页面使用哪个 HTML 版本进行编写的指令
```
<html lang="en">  --->这里的lang="en"可以删除，如果不删除的，用谷歌之类打开，它会认为是英文的，会自动给翻译（如果设置了自动翻译的话）

<head>  --->头部标签

<meta charset="UTF-8">  ---> 设置编码为UTF-8

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<meta http-equiv="X-UA-Compatible" content="ie=edge">

<meta name="author" content="violi"> --->作者名称

    <title>网页标题</title>

</head>

<body>  --->body标签 主要的页面元素就是在body标签中完成的

    <h1>这是标题标签</h1>  

    <div>这里是内容</div>

</body>

</html>
```



**标签一般分为单标签和双标签:**

单标签：<br />换行 <hr />水平分割线 <img>图片  <input>输入框 <meta> <link>

双标签：<em></em>  <i></i>斜体  <b></b>   <strong></strong>加粗  <font></font>字体<p></p>段落  <u></u>下划线   <del></del>删除线  <div></div>元素标签    等等



**行内元素**

1、<a>标签可定义锚;

2、<i>斜体文本效果 

3、<img/>向网页中嵌入一幅图像

4、<b>字体加粗；

5、<input/>输入框

6、<br/>换行

7、<big>大号字体加粗

8、<cite>引用进行定义

9、<code>定义计算机代码文本

10、<dfn>定义一个定义项目

11、<em>定义为强调的内容

12、<abbr> 表示一个缩写形式;

13、<acronym>定义只取首字母缩写;

14、<bdo>可覆盖默认的文本方向



**块状元素**

默认自动换行，类似容器的作用。

1、<address>定义地址

2、<caption>定义表格标题

3、<dd>定义列表中定义条目

4、<div>定义文档中的分区或节

5、<dl>定义列表

6、<dt>定义列表中的项目

7、<fieldset>定义一个框架集

8、<form>创建 HTML 表单

9、<h1>定义最大的标题

10、<h2>定义副标题

11、<h3>定义标题

12、<h4>定义标题

13、<h5>定义标题

14、<h6>定义最小的标题



**HTML语义化**

语义化标签能让浏览器更好的读取页面结构。再就是便于团队开发和维护，语义化更具可读性，遵循W3C标准的团队都遵循这个标准，可以减少差异化。



常用的语义化标签包括

<header></header>头部

<nav></nav>导航栏

<section></section>区块（有语义化的div）

<main></main>主要区域

<artical></artical>主要内容

<aside></aside>侧边栏

<footer></footer>底部

如图：

![img](C:/Users/yafei/AppData/Local/YNote/data/m15508511041_1@163.com/cc1721c911bf4ede8047c029eb6f0ebd/clipboard.png)



**常用特殊字符**

1、特殊字符：空格：&nbsp

2、显示大于和小于号：小于&lt  大于&gt

3、版权：&copy