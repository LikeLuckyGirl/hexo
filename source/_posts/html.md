---
title: html
date: 2024-11-20 17:28:55
tags: 专升本
---
## 一
### 基本标签
#### 开发工具
   写字板，notepad++，Dreamweaver，Hbuilder等
   编写的默认文件类型是文本文件，扩展名为txt，需要另存网页文件扩展名为html
#### Internate服务
   WWW（world wide web万维网）
   http（超文本传输协议）
   URL（唯一资源定位）
   E-mail（电子邮件）
   FTP（文件传输协议）
   Telnet（远程登录服务）
   W3C 万维网联盟
   B/S 浏览器和服务器
   静态网页和动态网页
 #### 网页文件结构标签
   HTML版本：我们学的HTML = HTML4.01 + HTML5
```html
<!DOCTYPE html>文档声明
<html>根标签
<head>头部标签
<title>网页标题（显示在页面标题栏）</title>
<meta charset="utf-8"/>元数据标签，定义页面特殊信息，如关键字，编码等提供给浏览器而不给人看，一般不显示。 </head>
</head>
<body>
窗体标签，网页显示的内容包含在本标签内。
</body>
</html>
```

#### * 文本的基本标签(元素）
```html
<h1>,<h2>,<h3>,<h4>,<h5>,<h6>(文本标题，h1最大，h6最小)
<p>(文本段落标签)
<!--html注释 -->
<hr />水平线标签
<br />换行标签
<i>斜体
<b>、<strong>粗体
<sup>上标
<sub>下标
<pre>预排版格式
<del>删除线
<u>、<ins>下划线
<font size="5" face="楷体" color="red">白日依山尽</font>
<div>块状容器
<span>行内容器
```
#### * 字符实体
```html
&nbsp；空格 
&gt；大于号
&lt；小于号
&copy；版权号
&reg；注册号
```

#### * 列表种类
```html
有序列表(类型包括1,a,A,i,I)
<ol type="">
<li>item1</li>
<li>item2</li>
</ol>
无序列表(类型包括disc,circle,square)
<ul type="">
<li>item1</li>
<li>item2</li>
</ul>
定义列表
<dl>
<dt>HTML</dt>
<dd>网页架构语言</dd>
<dt>CSS</dt>
<dd>网页样式语言</dd>
</dl>
```

#### * 标签和属性
```html
语法：<标签 属性="值">元素内容</标签>
针对body标签使用text属性设定文本颜色 <body text="red">红色段落</body>

bgcolor背景颜色。<body bgcolor="red">红色背景段落</p>
style样式。<p style="color:red;background-color:yellow;">黄色背景的红色文字的段落</p>

html的注释<!--注释内容-->
```
#### 练习
      第1章 基本标签
      一、单选题

      1、下面哪一个标签不能放在head标签内？（    ）
      A. title标签                 B. style标签
      C. body标签                  D. script标签
      2、如果网页中出现乱码，我们一般使用（     ）来解决。
      A. <meta charset="utf-8" />  B. <style type="text/css"></style>
      C. <script></script>         D. <link type="text/css" rel="stylesheet" href="css/index.css">
      3、下面选项中，属于HTML正确注释方式是（     ）。
      A. //注释内容                 B. /*注释内容*/
      C. <!--注释内容-->            D.//注释内容//  
      4、以下标记符中，用于设置页面标题的是（      ）。
      A <title>               B <caption>          
      C <head>            D <html>
      5、以下标记符中，没有对应的结束标记的是（      ）。
      A <body>    B <br>      
      C <html>     D <title>
      6、显示在浏览器中的内容必须写在HTML文件的（  ）标记内。
      A <body>    B <head>      
      C <link>     D <title>
      7、Dreamweaver和Hbuilder是（       ）软件。
      A 图像处理软件  B 网页编辑      
      C 字处理    D 动画处理
      8、一个网站是通过（      ）将很多网页链接在一起。
      A 文字    B 多媒体      
      C 超链接     D 图像
      9、下面不是常用浏览器软件的是（       ）。
      A Internet Explorer    B word      
      C Firefox     D Google Chrome

      二、判断题

      10、HTML是一种文件传输协议。
      11、网页中可以插入的图像文件没有格式限制。
      12、HTML文档是普通的文本文件，它可以用任意文本编辑器。

      三、填空题

      13、标记是HTML中的主要语法，分___标记和___标记两种。大多数标记是___出现的，由___标记和___标记组成。
      14、把HTML文档分为___和___两部分。___部分就是在Web浏览器窗口的用户区内看到的内容，而___部分用来设置该文档的标题（出现在Web 浏览器窗口的标题栏中）和文档的一些属性。

      四、编程题

      15、不借助开发工具代码提示，默写HTML基本结构。

      第2章 文本

      一、单选题
      1、选出你认为最合理的定义标题的方法是（  ）。
      A. <div>文章标题</div>                B. <p><b>文章标题</b></p>
      C. <h1>文章标题</h1>                  D. <strong>文章标题</strong>
      2、如果想要实现粗体效果，我们可以使用（   ）标签来实现。
      A. <strong></strong>                 B. <em></em>
      C. <sup></sup>                       D.<sub></sub>
      3、下面有关自闭合标签说法不正确的是（   ）。
      A. 自闭合标签只有开始符号没有结束符号    B. 自闭合标签可以在内部插入文本或图片
      C. meta标签是自闭合标签                D. hr标签是自闭合标签
      4、在浏览器默认情况下，下面有关块元素和行内元素说法不正确的是（  ）。
      A. 块元素独占一行                   B. 块元素内部可以容纳块元素
      C. 块元素内部可以容纳行内元素        D. 行内元素可以容纳块元素
      5、下面标签中，哪一个不是块元素？（  ）
      A. strong           B. p            
      C. div             D. hr

      第3章 列表
      一、单选题
      1、在下面几种列表形式中，哪一种在HTML5中已经被废弃了。（   ）
      A. 有序列表ol                    B.无序列表ul
      C. 定义列表dl                    D.目录列表dir
      2、下面哪种列表我们在实际开发中是用得最多的？（  ）
      A. 有序列表ol                    B.无序列表ul
      C. 定义列表dl                    D.目录列表dir
      3、下面有关ul元素（不考虑嵌套列表）说法不正确的是（   ）。
      A. ul元素的子元素只能是li，不能是其他元素
      B. ul元素内部的文本，只能在li元素内部添加，不能在li元素外部添加
      C. 绝大多数列表都是使用ul元素来实现，而不是ol元素
      D. 我们可以在ul元素中直接插入div元素
      4、下面有关HTML语义化不正确的是（   ）。
      A. 对于大多数标签实现的效果，我们完全可以使用div和span来代替实现
      B. 学习HTML目的在于：在需要的地方，用正确的标签
      C. 语义化对于搜索引擎优化来说是非常重要的
      D. 语义化目的在于提高可读性和可维护性
      二、填空题
      5、列表（List），顾名思义就是  。
      6、常用的列表有（  ）、（   ）和（  ）三种。
      7、无序列表标记<ul>的type属性可以指定出现在列表项前的项目符号的样式，
      其取值可以是：（   ）、（   ）和（   ）三种。
      8、有序列表标记<ol>的type属性可以指定出现在列表项前的项目编号的样式，
      其取值可以是：（   ）、（   ）、（   ）、（   ）和（   ）五种。
      9、使用有序列表标记的（   ）属性后，用户则可改变编号的起始值。
      该属性值是一个（   ），表示从哪一个数字或字母开始编号。
      10、使用列表项标记<li></li>的type属性，用户可以指定（   ）。
      11、使用列表项标记<li></li>的（   ） 属性，可以改变当前列表项的编号大小，
      并会影响其后所有列表项的编号大小。但该属性只适用于（   ）中 。


      第1章 基本标签
      参考答案：1C,2A, 3C，4A，5B，6A，7B，8C，9B，
      10错，11错，12错，13（单，双，成对，开始，结束），14（头部，主体，主体，头部）
      15
      <!DOCTYPE html>
      <ht ml>
      <head>

      </head>
      <body>

      </body>
      </html>
      第2章 文本
      参考答案：1C、2A、3B、4D、5A

      第3章 列表
      参考答案: 1D, 2B, 3D, 4A,
      5在网页中将相关资料以条目的形式有序或者无序排列而形成的表
      6无序列表、有序列表和定义列表
      7 disc、 circle和square  
      8 1 、 a 、 A 、 i  和 I  
      9 START，整数
      10 单个列表项的符号 （对于无序列表而言）或编号（对于有序列表而言）  
      11 VALUE，有序列表



### 图片和超链接
#### * 图片加载
```html
<img src="url" alt="" title="" />
   url-unique resource locator唯一资源定位-路径-（相对，绝对路径）
```
##### 图片的种类
   jpg 有损压缩，色彩丰富，如照片、高清图片等。体积较大，不支持透明。
   png 无损压缩不适合存储颜色丰富的图片，体积较小，支持透明。可以用来制作网站logo
   gif 效果最差，它适合制作动画，QQ发的动图都是gif格式的。
##### 图片标签属性
   src="url图片路径"
   alt="浏览器查看替代图片的提示文字"
   title="用户将鼠标悬浮图片上可以查看显示的信息"
   width="5px"代表宽度我5像素，像素px代表计算机屏幕中最小的一个点
   height="px"代表高度

#### * 超链接制作
```html
<a href="url" target="_blank">文字超链接</a>
```
##### 超链接标签属性
href="url超链接跳转的路径"
target="超链接窗口打开方式,默认取值 _self,取值有_blank表示在新窗口打开,_parent等"
##### 超链接的种类
```html
内部和外部:跳转到网站内部网页的叫内部超链接；到外网地址的叫外部超链接
<a href="1基本标签.html">内部超链接</a>
<a href="http://www.baidu.com">外部超链接</a>

邮箱超链接:<a href="mailto:yanghp@sie.edu.cn">联系我</a>
文件超链接:<a href="a.doc|a.xls|a.ppt|a.zip">文件超链接（打开或下载文件）</a>
锚点超链接:<a href="#idname">锚点超链接</a>, 锚点 <div id="idname">点击锚点超链接跳到此处</div>
空链接：<a href="#">空链接</a>
图片超链接:超链接内容为文字的叫文字超链接，内容为图片的叫图片超链接
<a href="url">文字超链接</a>
<a href="url"><img src="a.jpg" /></a>
```
#### * 绝对路径和相对路径
绝对路径，指的是图片完整路径。分以下两种情况。
（1）带盘符的文件的完整路径:c:/img/a.jpg
（2）带域名的文件的完整路径:http://www.sie.edu.cn/a.jpg
相对路径，指的是图片相对当前页面的位置，主要有以下三种情况。
（1）当前目录： src="a.jpg"
如果网页文件和图片文件在同一个目录里，直接写图片文件名即可。
（2）当前目录上一层： src="../a.jpg"
../表示当前文件所在目录的上一级目录，../../表示当前文件目录的上一级目录的上一级目录。
（3）下级目录：src="图片保存的文件夹名/a.jpg"
当前文件与保存图片的文件夹在同一级目录，直接写图片保存的文件夹名和文件即可。
#### 练习
```html
一、单选题
1、在img标签中，（   ）属性的内容是提供给搜索引擎看的。
    A. src          B.alt          C.title           D.class

2、下面说法，正确的是（   ）。
    A.当鼠标移到图片上时，就会显示img标签alt属性中的文字
    B. src是img标签必不可少的属性，只有定义它之后图片才可以显示出来
    C. 在实际开发中，我们常用的是绝对路径，很少用到相对路径
    D. 如果想要显示一张动画图片，可以使用png格式来实现
   
3、下列不属于网页中常用图片格式是（      ）。
A. JPG          B. PNG          C. GIF           D. MP4

4、在HTML中，关于img标签说法错误的是（      ）。
A. img标签可用于在网页中插入图片。
    B. img标签是行级标签。
    C. img标签的title属性可指定替代文本。
    D. img标签的src属性用于指定图片路径。

2 超链接
一、单选题
1、想要使得超链接以新窗口的方式打开网页，需要定义target属性值为（   ）。
A. _self            B._blank        
C._parent                   D. _top
2、我们可以使用（   ）快速定位到当前页面的某一部分。
    A. 外部链接                B.锚点链接
    C. 特殊链接                 D.target属性
3、下面有关超链接的说法中，正确的是（  ）。
    A. 不仅文本可以设置超链接，图片也可以设置超链接
    B. 锚点链接属于外部链接的其中一种
    C. 可以使用src属性指定超链接的跳转地址
    D. 可以使用target="-blank";指定超链接在新窗口打开  
4、下列哪一项是在新窗口中打开网页文档（    ）。
   A．_self   B．_blank   
   C．_top    D．_parent
5、在网页中，必须使用（  A    ）标记来完成超级链接。
A．<a>…</a>    B．<p>…</p>　 　 
C．<link>…</link>　　　 D．<li>…</li>
6、超链接是建立网站、网页主要元素之一。若要建立在同一网页内的链接，应采用以下（　　）链接形式。
A．链接到一个E-mail         B．书签式链接
C．框架间链接               D．链接到一个网站
7、关于超链接，（　  ）的说法是正确的。
A．不同网页上的图片或文本可以链接到同一网页或网站
B．不同网页上的图片或文本只能链接到同一网页或网站
C．同一网页上被选定的一个图片或一处文本可以同时链接到几个不同网站
D．同一网页上图片或文本不能链接到同一书签
8、若要在页面中创建一个图像超链接，要显示的图形为 myhome.jpg，所链接的地址为http://www.pcnetedu.com，以下用法中正确的是（     ）。
A．<a href=http://www.pcnetedu.com">myhome.jpg</a>
B．<a href="http://www.pcnetedu.com"><img src="myhome.jpg"></a>
C．<img src="myhome.jpg"><a href ="http://www.pcnetedu.com"></a>
D．<a href =http://www.pcneredu.com><img src="myhome.jpg">
9、以下创建mail链接的方法，正确的是（   ）。
A．<a href="master@163.com">管理员</a>
B．<a href="callto:master@163.com">管理员</a>
C．<a href="mailto:master@163.com">管理员</a>
D．<a href="Email:master@163.com">管理员</a>
10、下面是相对路径的是（    ）。
A．http://www.sina.com.cn     B． ftp://219.153.40.150
C．../a.html                  D． /a.html
11、下面哪组属性是用于设置图像映射的区域坐标的（   ）。
A．rec   B．circle  
C．poly   D．coords
12、在HTML中，以下（   ）标签表示超链接。
A．a   B．href  
C．link   D．hover
二、填空题
13、在HTML文件中，URL是(      ) 。
14、在HTML文件中，超链接可以分为(      ) 。
15、关于超链接，(     ) 属性用于指定链接的目标窗口。
参考答案：
1 图片
1B，2B，3D，4C
1B分析：
    alt属性的内容是提供给搜索引擎看的，title属性的内容是提供给用户看的，这两个不要搞混了。
2B 分析：
    A中，当鼠标移到图片上时，显示的是title属性中的文字；
    C中，在实际开发中，我们用的都是相对路径，几乎不会用绝对路径；
    D中，动画图片都是gif格式

2 超链接
参考答案：1B、2B、3A、4B、5A、6B、7A、8B、9C、10C、11D、12A，
13统一资源定位器、
14内部链接和外部链接 、
15target 
```


### 表格和框架
#### * 表格
#####  完整的表格
```html
<table>
    <caption>表格标题</caption>
    <tr>
        <th>单元格1</th>
        <th>单元格2</th>
    </tr>
    <tr>
        <td>单元格3</td>
        <td>单元格4</td>
    </tr>
</table>
```


##### 表格的标签
```html
<table>表格
<caption>表名称
<tr>行
<th>表头
<td>单元格（列）
```


##### 表格标签属性
```html
在表格（table）中使用的属性
border 表格边框宽度，默认是0，没有边框
width  表格宽度
height 表格高度
cellspacing 单元格间距
cellpadding 单元格内边距

在单元格（td）中使用的属性
rowspan="2" 相邻的上下单元格合并（2行合并）
colspan="3" 相邻的左右单元格合并（3列合并）

align  水平方向的对齐方式，取值可以是left（左），center（居中），right（右）
垂直方向的对齐方式，取值可以是top（顶），middle（居中），bottom（底）

<table border="1px" width="200" height="100" cellspacing="0">
<caption align="bottom">表名称在表格下面</caption>
<tr>
<td rowspan="3" >3个相邻单元格合并</td>
</tr>
</table>
 1.如果一个表格包括有 1 行 4 列，表格的总宽度为“699”，间距为“5”，填充为“0”，边框为“3”，
 每列的宽度相同，那么应将单元格定制为多少像素宽。（    ）
A. 126      B. 136       C. 147      D.167
解析：699去两个边框宽度2*3，去5个间距5*5，除以4；（699-6-25）/4=167, 选择D
```
#### 框架
##### 框架的结构
```html
<html>
<head>
<title>框架的应用</title>
</head>
<frameset rows="20%,*">,
<frame name="top" src="url指定框架内部的网页来源" />
<frameset cols="20%,*">
<frame name="left" src="url指定框架内部的网页来源"/>
<frame name="right" src="url指定框架内部的网页来源"/>
</frameset>
</frameset>
</html>
```
#####  框架的标签和属性
```html
<frameset>框架集
<frame>框架
rows="*,*,*" 垂直方向均分三等份
cols="20%,*" 水平方向左边窗口占20%，其余为右边窗口
name="top" 上面的窗口名称为top
src 指定要显示的网页url，并将其显示在框架窗口中。
超链接中target属性值如果是框架窗口名，则在该窗口中打开超链接的网页。
如：target="right" 则在右测窗口打开该超链接页面。
```
#### * 浮动框架
```html
通过<iframe>标签可以在网页的任何位置开辟一个窗口，显示一个网页。
<iframe src="url指定框架内部的网页来源" width="" height=""></iframe>
```
#### 练习
```html
第4章 表格
一、单选题
1、下面有关表格的说法正确的是（  ）。
    A. 表格已经被抛弃了，现在没必要学
    B. 我们可以使用表格来布局
    C. 表格一般用于展示数据
    D. 表格最基本的3个标签是：tr、th、td
2、以下选项中，哪个全部都是表格标记（      ）。
A．<table><head><tfoot>               B．<table><tr><td> 
C．<table><tr><tt>                    D．<thead><body><tr>
3、请选择可以使单元格中的内容进行左对齐的正确HTML标记（      ）。  
A．<td align="left">                   B．<td valign="left"> 
C．<td leftalign>                      D．<tdleft>
4、要使表格的边框不显示，应设置border的值是（      ）。
A．1        B．0   
C．2      D．3
5、以下标记中，用于定义一个单元格的是（      ）。
A．<td>&nbsp; </td>                 B．<tr>…</tr>
C．<table>…</table>                 D．<caption>…</caption>
6、若要使表格的行高为16pt，以下方法中，正确的是（     ）。
A．<table border=1  height="16">…</table>
B．<table border=1  height="16pt">…</table>
C．<table border=1  height="16px">…</table>
D．<table border=1  height="16cm">…</table>
二、填空题
7、表格的标记是_______，单元格的标记是_______。
8、表格的宽度可以用百分比和________两种单位来设置。
9、表格分行用到的标记是   _______。
10、请写出在网页中设定表格边框的厚度的属性_______；设定表格单元格之间宽度属性____________；设定表格内容与单元格间的距离属性_________。
11、请写出<caption align=bottom>表格标题</caption>功能是    _______。
12、<tr>….</tr>是用来定义      ；<td>…</td>是用来定义      ；<th>…</th>是用来定义________。
13、单元格垂直合并所用的属性是_____；单元格横向合并所用的属性是______。
14、利用<table></table>标记符的______属性可以控制表格边框的显示样式；利用<table></table>标记符的_______属性可以控制表格分隔线的显示样式。

第8章 框架
一、单选题
1、下面有关框架的说法中，正确的是（  ）。
    A. 我们一般使用frameset标签来实现在一个页面中嵌入另外一个页面
    B. 一般使用href属性来定义iframe的链接地址
    C. 可以使用width和height来分别定义iframe的宽度和高度
    D. iframe标签在HTML5标准中已经被废弃了，现在使用的都是frame标签
    分析：
    A中，应该是iframe标签，其中frameset标签在HTML5中已经被舍弃了；
    B中，应该是src属性；
    D中，frame标签在HTML5标准中已经被废弃了，现在使用的都是iframe标签
2、<frame>标签的哪个属性值代表要显示的网页的路径的值。（        ）
A. src              B. name
C. frameborder                 D. noresize
3、<frameset>标签的哪个属性代表要按行分布单个框架窗口。（        ）
A. rows              B. cols
C. src                         D. noresize

二、判断题

4、<frame>标签的frameborder属性用于设定边框，其值0为不显示，1为显示，边框无法调整粗细。（      ）
5、<frame>标签的scrolling属性值为no，代表要显示滚动条效果。（     ）

 
第4章 表格
参考答案：1C, 2B，3A，4B，5A，6B，
7<table>，<td>，
8像素，
9<tr>，
10<border>，cellspacing，cellpadding，
11在表格下方添加标题，
12表格的一行，一个单元格，表头，
13colspan，rowspan，
14frame，rules
1分析：
    A中，使用表格来布局的方式已经被抛弃，但是并不代表表格被完全抛弃了。在数据展示方面，表格还是首选；
    B中，表格布局已经被抛弃了，正确应该是使用浮动布局或定位布局（在CSS部分会学到）；
D中，表格最基本的3个标签是：table、tr、td
 
 第8章 框架
 参考答案：1C，2A，3A，4对，5错
```















---