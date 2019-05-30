**mata的一些用法：**

```
<!-- 针对手持设备优化，主要是针对一些老的不识别viewport的浏览器，比如黑莓 -->

<meta name="HandheldFriendly" content="true">

<!-- 微软的老式浏览器 -->

<meta name="MobileOptimized" content="320">

<!-- uc强制竖屏 -->

<meta name="screen-orientation" content="portrait">

<!-- QQ强制竖屏 -->

<meta name="x5-orientation" content="portrait">

<!-- UC强制全屏 -->

<meta name="full-screen" content="yes">

<!-- QQ强制全屏 -->

<meta name="x5-fullscreen" content="true">

<!-- UC应用模式 -->

<meta name="browsermode" content="application">

<!-- QQ应用模式 -->

<meta name="x5-page-mode" content="app">

<!-- windows phone 点击无高光 -->
```



```
1.添加对手机设备的支持

<meta name="viewport" content="width=device-width, initial-scale=1">

<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">（禁止缩放）

2.兼容IE

<meta http-equiv="X-UA-Compatible" content="IE=edge">

3.规定utf-8编码

<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

4.让搜索引擎搜索到关键字  **seo**

<meta name="Keywords" content="网页关键字">

<meta name="description" content="网页描述文字" />

5.设置双核浏览器的浏览模式

<meta name="renderer" content="webkit">

<meta name=“renderer” content=“webkit|ie-comp|ie-stand”>（分别为极速模式，兼容模式，以 

及IE模式）

6.产生特殊效果

< meta http-equiv="Page-Enter" content= "revealTrans(Duration=5.0,Transition=n)" >(n的取值范围为0-23)

7、标注作者： 

<meta name="author" content="二度空间"> 

8、控制页面缓冲，如不要页面缓冲的代码这样写： 

<meta http-equiv="Cache-Control" CONTENT="no-cache">

9.让网页每隔一段时间刷新一次，若要10秒刷新一次，代码这样写： 

<meta http-equiv="refresh" content="10"> 

10.让一个页面过上一定的时间，自动转到另一个页面或者站点去，如： 

< Meta HTTP-EQUIV="refresh" content="6; url=http://hi.baidu.com" >

content中的6表示时间，单位为秒，url=后面是你要转向的网址，若是与你当前网页在同一目录下，可以直接写上文件名，如： 

< Meta HTTP-EQUIV="refresh" content="6; url=page1.htm" >



**format-detection——格式检测，用来检测html里的一些格式，主要与以下几个设置：**

<meta name="format-detection" content="telephone=no">

<meta name="format-detection" content="email=no">

<meta name="format-detection" content="address=no">

telephone——主要作用是是否设置自动将你的数字转化为拨号链接；

email——告诉设备不识别邮箱，点击之后不发送

address——是否开启点击地址直接跳转地图的功能，默认开启。



**mata 中的****viewport** 

width	设置layout viewport  的宽度，为一个正整数，或字符串"width-device"

initial-scale	设置页面的初始缩放值，为一个数字，可以带小数

minimum-scale	允许用户的最小缩放值，为一个数字，可以带小数

maximum-scale	允许用户的最大缩放值，为一个数字，可以带小数

height	设置layout viewport  的高度，这个属性对我们并不重要，很少使用

user-scalable	是否允许用户进行缩放，值为 "no" 或 "yes", no 代表不允许，yes 代表允许集体参考： <https://www.runoob.com/w3cnote/viewport-deep-understanding.html>
```