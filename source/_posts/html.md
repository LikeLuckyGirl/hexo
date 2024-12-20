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
    <meta charset="utf-8"/>
    元数据标签，定义页面特殊信息，如关键字，编码等提供给浏览器而不给人看，一般不显示。
</head>
</head>
<body>
窗体标签，网页显示的内容包含在本标签内。
</body>
</html>
```

####        * 文本的基本标签(元素）

```html

<h1>,
    <h2>,
        <h3>,
            <h4>,
                <h5>,
                    <h6>(文本标题，h1最大，h6最小)
                        <p>(文本段落标签)
                            <!--html注释 -->
                        <hr/>
                        水平线标签
                        <br/>换行标签
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

####        * 字符实体

```html
&nbsp；空格
&gt；大于号
&lt；小于号
&copy；版权号
&reg；注册号
```

####        * 列表种类

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

####        * 标签和属性

```html
语法：
<标签 属性="值">元素内容</标签>
针对body标签使用text属性设定文本颜色
<body text="red">红色段落</body>

bgcolor背景颜色。
<body bgcolor="red">红色背景段落</p>
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

####        * 图片加载

```html
<img src="url" alt="" title=""/>
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

####        * 超链接制作

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
锚点超链接:<a href="#idname">锚点超链接</a>, 锚点
<div id="idname">点击锚点超链接跳到此处</div>
空链接：<a href="#">空链接</a>
图片超链接:超链接内容为文字的叫文字超链接，内容为图片的叫图片超链接
<a href="url">文字超链接</a>
<a href="url"><img src="a.jpg"/></a>
```

####        * 绝对路径和相对路径

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
C．
<link>…</link>　　　 D．
<li>…</li>
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
C．<img src="myhome.jpg"><a href="http://www.pcnetedu.com"></a>
D．<a href=http://www.pcneredu.com><img src="myhome.jpg">
    9、以下创建mail链接的方法，正确的是（ ）。
    A．<a href="master@163.com">管理员</a>
    B．<a href="callto:master@163.com">管理员</a>
    C．<a href="mailto:master@163.com">管理员</a>
    D．<a href="Email:master@163.com">管理员</a>
    10、下面是相对路径的是（ ）。
    A．http://www.sina.com.cn B． ftp://219.153.40.150
    C．../a.html D． /a.html
    11、下面哪组属性是用于设置图像映射的区域坐标的（ ）。
    A．rec B．circle
    C．poly D．coords
    12、在HTML中，以下（ ）标签表示超链接。
    A．a B．href
    C．link D．hover
    二、填空题
    13、在HTML文件中，URL是( ) 。
    14、在HTML文件中，超链接可以分为( ) 。
    15、关于超链接，( ) 属性用于指定链接的目标窗口。
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

####        * 表格

##### 完整的表格

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
        <td rowspan="3">3个相邻单元格合并</td>
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
    <frame name="top" src="url指定框架内部的网页来源"/>
    <frameset cols="20%,*">
        <frame name="left" src="url指定框架内部的网页来源"/>
        <frame name="right" src="url指定框架内部的网页来源"/>
    </frameset>
</frameset>
</html>
```

##### 框架的标签和属性

```html

<frameset>框架集
    <frame>
    框架
    rows="*,*,*" 垂直方向均分三等份
    cols="20%,*" 水平方向左边窗口占20%，其余为右边窗口
    name="top" 上面的窗口名称为top
    src 指定要显示的网页url，并将其显示在框架窗口中。
    超链接中target属性值如果是框架窗口名，则在该窗口中打开超链接的网页。
    如：target="right" 则在右测窗口打开该超链接页面。
```

####        * 浮动框架

```html
通过
<iframe>标签可以在网页的任何位置开辟一个窗口，显示一个网页。
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
A．
<table>
    <head>
        <tfoot> B．
        <table>
            <tr>
                <td>
                    C．
                    <table>
                        <tr><tt> D．
                            <thead>
    <body>
    <tr>
        3、请选择可以使单元格中的内容进行左对齐的正确HTML标记（ ）。
        A．
        <td align="left"> B．
        <td valign="left">
            C．
        <td leftalign> D．
            <tdleft>
                4、要使表格的边框不显示，应设置border的值是（ ）。
                A．1 B．0
                C．2 D．3
                5、以下标记中，用于定义一个单元格的是（ ）。
                A．
        <td>&nbsp;</td>
        B．
    <tr>…</tr>
    C．
    <table>…</table>
    D．
    <caption>…</caption>
    6、若要使表格的行高为16pt，以下方法中，正确的是（ ）。
    A．
    <table border=1 height="16">…</table>
    B．
    <table border=1 height="16pt">…</table>
    C．
    <table border=1 height="16px">…</table>
    D．
    <table border=1 height="16cm">…</table>
    二、填空题
    7、表格的标记是_______，单元格的标记是_______。
    8、表格的宽度可以用百分比和________两种单位来设置。
    9、表格分行用到的标记是 _______。
    10、请写出在网页中设定表格边框的厚度的属性_______；设定表格单元格之间宽度属性____________；设定表格内容与单元格间的距离属性_________。
    11、请写出
    <caption align=bottom>表格标题</caption>
    功能是 _______。
    12、
    <tr>….</tr>
    是用来定义 ；
    <td>…</td>
    是用来定义 ；
    <th>…</th>
    是用来定义________。
    13、单元格垂直合并所用的属性是_____；单元格横向合并所用的属性是______。
    14、利用
    <table></table>
    标记符的______属性可以控制表格边框的显示样式；利用
    <table></table>
    标记符的_______属性可以控制表格分隔线的显示样式。

    第8章 框架
    一、单选题
    1、下面有关框架的说法中，正确的是（ ）。
    A. 我们一般使用frameset标签来实现在一个页面中嵌入另外一个页面
    B. 一般使用href属性来定义iframe的链接地址
    C. 可以使用width和height来分别定义iframe的宽度和高度
    D. iframe标签在HTML5标准中已经被废弃了，现在使用的都是frame标签
    分析：
    A中，应该是iframe标签，其中frameset标签在HTML5中已经被舍弃了；
    B中，应该是src属性；
    D中，frame标签在HTML5标准中已经被废弃了，现在使用的都是iframe标签
    2、
    <frame>
    标签的哪个属性值代表要显示的网页的路径的值。（ ）
    A. src B. name
    C. frameborder D. noresize
    3、
    <frameset>标签的哪个属性代表要按行分布单个框架窗口。（ ）
        A. rows B. cols
        C. src D. noresize

        二、判断题

        4、
        <frame>
        标签的frameborder属性用于设定边框，其值0为不显示，1为显示，边框无法调整粗细。（ ）
        5、
        <frame>
        标签的scrolling属性值为no，代表要显示滚动条效果。（ ）


        第4章 表格
        参考答案：1C, 2B，3A，4B，5A，6B，
        7
        <table>，
            <td>，
                8像素，
                9
                <tr>，
                    10
                    <border>，cellspacing，cellpadding，
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

## 题

```html
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
	A <title>     		   	     B <caption>          
	C <head>      			     D <html>
5、以下标记符中，没有对应的结束标记的是（      ）。
	A <body>  					 B <br>      
	C <html>   					 D <title>
6、显示在浏览器中的内容必须写在HTML文件的（  ）标记内。
	A <body>  					 B <head>      
	C <link>   					 D <title>
7、Dreamweaver和Hbuilder是（       ）软件。
	A 图像处理软件				 B 网页编辑      
	C 字处理  					 D 动画处理
8、一个网站是通过（      ）将很多网页链接在一起。
	A 文字  						 B 多媒体      
	C 超链接   					 D 图像
9、下面不是常用浏览器软件的是（       ）。
	A Internet Explorer  		 B word      
	C Firefox   				 D Google Chrome

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
	A. strong        				  B. p            
	C. div          				  D. hr

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
<html>
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

   1 图片
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
   A. _self           			B._blank
   C._parent                   D. _top
   2、我们可以使用（   ）快速定位到当前页面的某一部分。
   A. 外部链接              	 B.锚点链接
   C. 特殊链接               	 D.target属性
   3、下面有关超链接的说法中，正确的是（  ）。
   A. 不仅文本可以设置超链接，图片也可以设置超链接
   B. 锚点链接属于外部链接的其中一种
   C. 可以使用src属性指定超链接的跳转地址
   D. 可以使用target="-blank";指定超链接在新窗口打开
   4、下列哪一项是在新窗口中打开网页文档（    ）。
   A．_self  				B．_blank
   C．_top   				D．_parent
   5、在网页中，必须使用（  A    ）标记来完成超级链接。
   A．<a>…</a>   				B．<p>…</p>　 　
   C．<link>…</link>　　　		D．<li>…</li>
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
   A．rec  						B．circle
   C．poly  					D．coords
   12、在HTML中，以下（   ）标签表示超链接。
   A．a  						B．href
   C．link  					D．hover
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
   A．1 						  	   B．0
   C．2  							   D．3
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
   A. src				            		B. name
   C. frameborder			                D. noresize
   3、<frameset>标签的哪个属性代表要按行分布单个框架窗口。（        ）
   A. rows			            		B. cols
   C. src			                        D. noresize

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



   第7章 表单
   一、单选题
   1、大多数表单元素都是使用（   ）标签，然后通过type属性指定表单类型。
   A. input           			   B. textarea
   C. select          			   D. option
   2、下面表单元素中，有value属性的是（    ）。
   A. 单选框           			    B.复选框
   C. 下拉列表          			D.以上都是
   3、单行文本框使用（）实现，密码文本框使用（  ）实现，多行文本框使用（  ）实现。
   A. <textarea></textarea>        B. <input type="texarea" />
   C. <input type="text" />        D. <input type="password" />
   4、如果想要定义单选框默认选中效果，可以使用（  ）属性来实现。
   A. checked           B.selected
   C. type              D.以上都不是
   5、在表单中，input元素的type属性取值为（  ）时，用于创建重置按钮。
   A. reset             B. set
   C. button            D. submit
   6、下面有关表单的说法，正确的是（   ）。
   A. 表单其实就是表格，两者是一样的
   B. 下拉列表不属于表单，而是属于列表的一种
   C. 在表单中，group属性一般用于单选框和复选框分组
   D. 在表单中，value属性一般是为了方便JavaScript或服务器操作数据用的
   7、下面对于按钮的说法，不正确的是（   ）。
   A. 普通按钮一般情况下都是配合JavaScript来进行各种操作的；
   B. 提交按钮一般都是用来给服务器提交数据的；
   C. 重置按钮一般用来清除用户在表单中输入的内容
   D. 表单中的按钮更多的是使用button标签来实现
   8、在HTML中，<form method=post>，method表示(    )
   A. 提交的方式					B. 表单所用的脚本语言
   C. 提交的URL地址					D. 表单的形式
   9、增加表单的文本域的HTML代码是(    )
   A. <input type=submit></input>		B. <textarea name="textarea"></textarea>
   C. <input type=radio></input>		D. <input type=checkbox></input>
   10、以下关于<select>标记说法正确的是(   )
   A. <select>定义的表单元素在一个下拉菜单中显示选项
   B. rows和cols属性可以定义其大小
   C. <select>定义的表单元素是一个单选按钮
   D. <select>定义的表单元素是一个多选按钮
   11、现要设计一个可以输入电子邮件地址的web页，应该使用的语句是(    )
   A. <input type=radio>			B. <input type=text>
   C. <input type=password>		D. <input type=checkbox>
   12、在网页中创建表单应使用下列(    )标签。
   A. <input >				        B. <option>
   C. <select>			            D. <form>
   13、下列(    )属性可以设置textarea控件显示的行数。
   A. name			   				B. cols
   C. rows							D. disabled
   二、填空题
   14、 <form>标记中，________属性的作用就是指出该表单所对应的处理程序的位置；______  ___属性用于指定该表单的运行方式。
   15、method属性的取值可以为________和_________之一，其默认方式是_______。
   16、 <input>标记中，_______属性的值是相应处理程序中的变量名；____属性用于指出用户输入值的类型。
   17、<input>标记中,type属性有九种取值，分别是：_____。
   18、当type=text时，<input>标记除了有两个不可默认的属性________和________外，还有三个可选的属性：_______、_______和_______。
   19、当type=_______时，浏览器会在相应位置产生一个图像按钮，其中，________属性是必需的，它用于设置图像文件的路径。
   三、编程题
   20、使用这一章学到的表单标签，制作表单页面。

   第7章 表单
   参考答案：1A、2D、3D、4A、5A、6D、7D、8A、9B、10A、11B、12D，13C，
   14_ action method、
   15_ get post get__、
   16_name__type、
   17text，submit，reset，password，checkbox，radio，image，hidden，file、
   18_name _type _maxlength__size__value_、
   19_image_src_
   20、    实现代码如下：
   <!DOCTYPE html>
   <html>
   <head>
   <meta charset="utf-8" />
   <title></title>
</head>
<body>
<form  method="post">
   昵称：<input type="text"/><br/>
   密码：<input type="password"/><br/>
   邮箱：<input type="text"/>
   <select>
      <option>qq.com</option>
      <option>163.com</option>
      <option>foxmail.com</option>
   </select>
   <br/>
   性别：<input type="radio" name="gender" checked/>男
   <input type="radio" name="gender" />女
   <br/>
   爱好：<input type="checkbox" name="hobby" />旅游
   <input type="checkbox" name="hobby" />摄影
   <input type="checkbox" name="hobby" />运动
   <br/>
   个人简介：<br/>
   <textarea></textarea><br/>
   上传个人照片：<br/>
   <input type="file" />
   <hr />
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="button" value="立即注册"/>
</form>
</body>
</html>

第9章 CSS选择器
一、单选题
1、下面说法中，正确的是（  ）。
A. 现在已经是CSS3时代了，CSS2没必要再去学
B. 一般使用script标签来引用外部样式表
C. 在实际开发中，一般使用外部样式表的多
D. 内部样式表和行内样式表在实际开发中一点用处都没有
分析：
A中，我们常说的CSS3一般指的是相对于CSS2新增的内容，准确来说，你要学的CSS应该是“CSS2+CSS3”；
B中，应该是link标签；
D中，在处理个体样式或者样式微调时，一般是用内部样式表和行内样式表来处理，由于内容过多，这里不详细展开，具体请参考本书的进阶篇《Web前端开发精品课·HTML与CSS进阶教程》

2、每一个样式声明之后，要用（   ）表示一个声明的结束。
A. 逗号          B. 分号
C. 句号          D. 顿号
3、下面哪一项是CSS正确的语法结构？（  ）
A. body:color=black                      B. {body;color:black}
C. {body:color=black;}                   D. body{color:black;}
4、下面有关id和class的说法中，正确的是（   ）。
A. id是唯一的，不同页面中不允许出现相同的id
B. id就像你的名字，class就像你的身份证号
C. 同一个页面中，不允许出现两个相同的class
D. 可以为不同的元素设置相同的class来为他们定义相同的css样式
分析：
A中，在同一个页面是不允许出现相同的id，但是在不同页面中是允许有相同的id；
B中，id是唯一的，就像你的身份证号，但是class是不唯一的，就像你的名字；
C中，同一个页面中，一般用相同的class设置相同的CSS样式，当然允许出现两个相同的class；
5、下面有关选择器的说法中，不正确的是（  ）。
A. 在class选择器中，我们只能对相同的元素定义相同的class属性
B. 后代选择器选择的不仅是子元素，还包括它的其他后代元素（如“孙元素”）
C. 群组选择器可以对几个选择器进行相同的操作
D. 想要为某一个元素定义样式，我们可以使用不同的选择器来实现
分析：
A中，我们可以为相同的元素或者不同的元素定义相同的class属性，目的是用一个class就可以设置相同的样式；
二、编程题
6、下面有一段代码，如果我们想要选中所有的div和p，请用至少2种不同的选择器方式来实现，并且选出最简单的一种。
<!DOCTYPE html>
<html>
<head>
   <meta charset="utf-8" />
   <title></title>
</head>
<body>
<div></div>
<p></p>
<p></p>
<strong></strong>
<span></span>
</body>
</html>


第9章 CSS选择器
参考答案：1C，2B，3D，4D，5A
6我们可以为元素添加id或class来选取。

第10章 字体样式
一、单选题
1、CSS中可以使用（   ）属性来定义字体粗细。
A. font-family       B. font-size      C. font-weight     D. font-style
2、如果想要实现字体颜色为白色，可以使用定义color属性值为（   ）。
A. #000000         B. #FFFFFF      C. wheat         D.black
分析：
#000000表示黑色，#FFFFFF表示白色，这两个颜色值还是要熟悉一下的。
3、下面有关字体样式，说法正确的是（   ）。
A. font-family属性只能指定一种字体类型
B. font-family属性可以指定多种字体类型，并且浏览器是按照从右到左的顺序选择
C. 在实际开发中，font-size很少取“关键字”作为属性值
D. 在实际开发中，font-weight属性一般取100~900的数值
分析：
A中，font-family属性可以指定多种字体类型；
B中，font-family属性指定多种字体类型时，浏览器是从左到右进行解析的；
D中，在实际开发中，font-weight一般取值为关键字
4、下面选项中，属于CSS正确注释方式是（   ）。
A. //注释内容
B. /*注释内容*/
C. <!--注释内容-->
D.//注释内容//
5、下列选项中属于CSS字体类型的是（          ）。
A. font-family       B. font-size      C. font-weight     D. font-style
二、编程题
6、为下面这段文字定义字体样式，要求字体类型指定多种、大小为14px、粗细为粗体、颜色为蓝色。
“有规划的人生叫蓝图，没规划的人生叫拼图。”

第11章 文本样式
一、单选题
1、CSS使用（   ）属性来定义段落的行高。
A. height          B. align-height          C. line-height        D.min-height
2、CSS使用（  ）属性来定义字体下划线、删除线以及顶划线效果。
A. text-decoration                 B. text-indent
C. text-transform                  D.text-align
3、如果想要实现下图14-12所示的效果，我们可以使用（  ）来实现。


A. text-decoration:none;
B. text-decoration:underline;
C. text-decoration:line-through;
D. text-decoration:overline;
4、下面有关文本样式的说法中，正确的是（   ）。
A. 如果想要让段落首行要缩进2个字的间距，text-indent值应该是font-size值的4倍
B.“ text-align:center;”不仅可以实现文本水平居中，还可以实现图片水平居中
C. 我们可以使用line-height来实现一个段落的高度
D. 我们可以使用“text-transform:uppercase;”来将英文转换为小写形式
5、下列属性中属于CSS文本装饰的是（   ）。
A. text-decoration       B. text-align      C. text-overflow     D.text-indent
6、如果要设置段落首行缩进两个字符，将用到下列（   ）CSS属性。
A. text-decoration       B. text-align      C. text-overflow     D.text-indent

二、编程题
7、下面有一段代码，请在这段代码基础上使用正确的选择器以及这两章学到的字体样式、文本样式来实现图中的效果。
<!DOCTYPE html>
<html>
<head>
   <meta charset="utf-8" />
   <title></title>
</head>
<body>
<p>很多人都喜欢用战术上的勤奋来掩盖战略上的懒惰，事实上这种“<span>低水平的勤奋</span>”远远比懒惰可怕。</p>
<p>Remember: no pain, no gain！</p>
</body>
</html>

第12章 边框样式
一、单选题
1、如果我们想要定义某一个元素的右边框，宽度为1px，外观为实线，颜色为红色，正确写法应该是（  ）。
A. border:1px solid red;  		  	B. border:1px dashed red;
C. border-right:1px solid red;    		D. border-right:1px dashed red;
2、如果我们想要去掉某一个元素的上边框，下面写法中不正确的是（   ）。
A. border-top:not;    				B.border-top:none;
C. border-top:0;    				D.border-top:0px;
3、CSS文件的扩展名为（       ）。
A. .txt			B. .htm		C. .css		D. .html
4、以下的HTML中，哪个是正确引用外部样式表的方法？（      ）
A. <style src="mystyle.css">
   B. <link rel="stylesheet" type="text/css" href="mystyle.css">
                                                               C. <stylesheet>mystyle.css</stylesheet>
                                                                                           D.<script src=””>
   5、CSS的继承并不是完全的“克隆”，有些继承是不起作用的，在下面的几个属性中，那个继承是起作用的（    ）。
    A.  border　　	B. margin	　　C. font		D. padding
   6、在网页中最常用的单位是（      ）。
    A.  in	　　    B. cm	　　C. px	　　D. pc
   7、下列哪个选项的CSS语法是正确的？（     ）
    A. body:color=black　　　　 	B. {body:color=black(body}
   C. body {color: black}        	D. {body;color:black}
   8、下面那个语句是把段落的字体设置为黑体、18像素、红色字体显示（      ）
    A.  p{font-family:黑体；font-size:18pc; font-color:red}
   B.  p{font-family:黑体；font-size:18px; font-color:#ff0000}
   C.  p{font:黑体 18px #00ff00}
   D.  P{font-size:黑体}
   9、如何为所有的<h1>元素添加背景颜色？（       ）
    h1.all {background-color:#FFFFFF}
   h1 {background-color:#FFFFFF}
   all.h1 {background-color:#FFFFFF}
   h1{color:#FFFFFF}
   10、设置text-decoration属性的删除线的值为（      ）。
     A.  underline 	B.  overline  	C.  line-through		D.  blink
   11、设置字符间距为15px的语句为（     ）。
     A.  letter-spacing:15px     	B.  line-height:15px
                                                      C.  letter-height:15px      	D.  line-spacing:15px
   12、如何显示这样一个边框：顶边框10像素、底边框5像素、左边框20像素、右边框1像素（     ）。
     A.  border-width:10px 1px 5px 20px   B.  border-width:10px 20px 5px 1px
                                                                          C.  border-width:5px 20px 10px 1px   D.  border-width:10px 5px 20px 1px
   13、如何产生带有正方形的项目的列表？（    ）
     A.  list-type: square     	            B.  list-style-type: square
     C.  type: square                   	D.  type: 2
   14、在CSS语言中下列哪一项是"左边框"的语法？（      ）
                        A．border-left-width: <值>              B．border-top-width: <值>
                                                                                   C．border-left: <值>                   D．border-top-width: <值>
   15、如何去掉文本超级链接的下划线？( B )
   A．a {text-decoration:no underline}       B．a {underline:none}
   C．a {decoration:no underline}           D．a {text-decoration:none}
   16、下面（  ）是ID的样式规则定义。（      ）
     A. tr{clore:red;font-family:"隶书";font-size:24px;}
   B. .h2{color:red;font-family:"隶书";}
   C. #grass{color:green;font- family:"隶书"; font-size:24px;}
   D. p{background-color:#CCFF33;text-align:left;}
   17、若要以加粗宋体、12号字显示“vbscript”以下用法中，正确的是（      ）
     A.<b><font style='font-size:10px'2>vbscript</b></font>
                                                      B.<b><font face=”宋体” style='font-size:10px'2>vbscript</font></b>
                                                                                                                    C.<b><font size=“宋体”style='font-size:10px'2>vbscript</b></font>
                                                                                                                                                                              D.<b><font size=“宋体” fontstyle='font-size:10px'2>vbscript</b></font>
   18、以下有关样式表项的定义中，正确的是（      ）
     A. h1{font-family:楷体_gb2312, text-aligh:center}
   B. h1{font-family=楷体_gb2312, text-aligh=center}
   C. h1{font-family:楷体_gb2312; text-aligh:center}
   D. h1{font-family=楷体_gb2312; text-aligh=center}
   19、下列代码段是某页面的样式设置：
<style type="text/css">
                           .blue { color:blue }
   .red { color:red }
</style>
请将页面中的第一个h1标题设置为红色，第一个段落设置为蓝色，正确的是（      ）
A． <h1 id="red">第一个标题<h1><p id="blue">第一个段落</ p >
B． <h1 color:red>第一个标题<h1><p color:blue>第一个段落</ p>
C． <h1 class="red">第一个标题<h1><p class="blue">第一个段落</ p >
D． <h2 class="red">第一个标题<h2><h1>第一个标题<h1><p class="blue">第一个段落</ p >
20、若要使表格的行高为16pt，以下方法中，正确的是（      ）
    A．<table border=1 style=” line-height:16”>…</table>
    B．<table border=1 style=”line-height:16pt”>…</table>
    C．<table border=1 lineheight=16pt”>…</table>
    D．<table border=1 lineheight=”16pt”>…</table>
二、填空题
    21、CSS的英文名为__________，译成中文的意思为_____。
    22、CSS里四种不同的定义分别为：__、___、______、________。
    23、CSS的选择符类型为________________、___________。

第13章 列表样式
    一、单选题
        1、下面对于列表说法中，叙述错误的是（   ）。
            A. list-style-type属性是在li元素中设置的
            B. 我们可以使用“list-style-type:none;”去除列表项符号
            C. 大多数列表我们都是使用ul元素，而不是使用ol元素
            D. 不管是有序列表还是无序列表，我们都是使用list-style-type属性来定义列表项符号
            分析：    A中，list-style-type属性是在ul或ol元素中设置的，而不是li元素；
    二、编程题
        2、定义一个列表，每一个列表项都是一个超链接，并且要求去除以及列表项符号以及超链接下划线，超链接文本颜色为粉红色，并且点击某一个列表项会以新窗口的形式打开。

第14章 表格样式
    一、单选题
        1、CSS可以使用（  ）属性来合并表格边框。
            A. border-width                        B. border-style
            B. border-collapse                      D. border-spacing
        2、下面有关表格样式，说法不正确的是（  ）。
            A. border-collapse只限用于表格，不能用于其他元素
            B. caption-side、border-collapse、border-spacing这3个一般在table元素中设置
            C. 可以使用“border-collapse: separate;”来将表格边框合并
            D. 如果要为表格添加边框，我们一般需要同时对table、tr、td这几个进行设置
            分析：
            C中，应该是“border-collapse: collapse;”
        3、设置相邻单元格的距离，应该使用下列（     ）属性。
            A. border-collapse       B. border-spacing      C. caption-side     D.empty-cells
            4、设置表格标题，应该使用下列（     ）属性。
            A. border-collapse       B. border-spacing      C. caption-side     D.empty-cells

第15章 图片样式
    一、单选题
		1、CSS可以使用（   ）属性来实现图片水平居中。
            A. text-indent                  B. text-align
            C. vertical-align                 D.float
        2、下面有关图片样式，说法正确的是（  ）。
            A. 由于img元素不是块元素，因此设置width和height无效
            B. 可以使用vertical-align属性来实现图片在div元素中垂直居中
            C. “text-align:center;”不仅能实现图片水平居中，也能实现文本水平居中
            D. 可以使用text-align实现文字环绕图片的效果
第16章 背景样式
    一、单选题
        1、CSS可以使用（  ）属性来设置文本颜色。
            A. color          B.background-color       C.text-color          D. font-color

        2、下面有关背景样式，说法不正确的是（  ）。
            A. 默认情况下，背景图片是不平铺的
            B. color设置的是文本颜色，background-color设置的是背景颜色
            C. CSS Spirit技术是借助background-position属性来实现的
            D. 我们可以使用“background-repeat:repeat-x;”来实现背景图片在X轴方向平铺
第17章  超链接样式
    一、单选题
        1、下面哪一个伪类选择器是用于定义鼠标经过元素时样式的？（   ）
            A.  a:link         B.  a :visited          C.  a:hover          D.  a :active
        2、在实际开发中，如果想要定义超链接未访问时的样式，可以使用（   ）。
            A.  a{}           B.  a:visited{}          C.  a:hover{]        D.  a:active{}
        3、我们可以使用（   ）来实现鼠标悬停在超链接上时为无下划线效果。
            A. a{text-decoration:underline;}                B. a{text-decoration:none;}
            C. a:link{text-decoration:underline;}             D. a:hover{text-decoration:none;}
        4、下面有关超链接样式说法中，正确的是（   ）。
            A. 对于超链接的下划线，我们可以使用“text-decoration:none;”去掉
            B. cursor属性自定义鼠标样式时，使用的图片文件后缀名可以是.png
            C. :hover伪类只能用于a元素，不能用于其他元素
            D. 对于超链接来说，在实际开发中，我们一般只会定义2种状态：鼠标经过状态和点击后状态

    二、编程题
        5、在网页中添加一段文本链接，并且设置其在不同的状态下显示不同的效果。要求：
            （1）未访问时：没有下划线，颜色为红色
            （2）鼠标经过时：有下划线，颜色为蓝色

第10章 字体样式
    参考答案：1C,2B，3C，4B，5A
    6    实现代码如下：
        <!DOCTYPE html>
        <html>
        <head>
            <meta charset="utf-8" />
            <title></title>
            <style type="text/css">
                p{
                    font-family:"微软雅黑","Times New Roman",Caribli;
                    font-size:14px;
                    font-weight:bold;
                    color:blue;
                }
            </style>
        </head>
        <body>
            <p>有规划的人生叫蓝图，没规划的人生叫拼图。</p>
        </body>
        </html>
            第11章 文本样式
            参考答案：1C，2A，3C，4B，5A，6D，7
            4分析：
            A中，text-indent值应该是font-size值的2倍
            C中，line-height定义的是一行文字的高度。如果想要定义段落的高度，应该用height；
            D中，应该是“text-transform:lowercase;”
            7  实现代码如下：（出于选择器的不同，答案也不唯一）
            <!DOCTYPE html>
            <html>
            <head>
               <meta charset="utf-8" />
               <title></title>
               <style type="text/css">
                  p
                  {
                     font-size:14px;
                     text-indent:28px;
                  }
                  #p2
                  {
                     text-transform:uppercase;
                  }
                  span
                  {
                     font-weight:bold;
                     text-decoration:underline;
                  }
               </style>
            </head>
            <body>
            <p id="p1">很多人都喜欢用战术上的勤奋来掩盖战略上的懒惰，事实上这种“<span>低水平的勤奋</span>”远远比懒惰可怕。</p>
            <p id="p2">Remember: no pain, no gain！</p>
            </body>
            </html>
            第12章 边框样式
            参考答案：1C，2A，3C，4B，5C，6C，7C，8B，9B，10C，11A，12A,13B,14C,15D,16C,17B,18A,19C，20B,
            21Cascading Style Sheet，层叠样式，
            22直接定义标记的style属性，定义内部样式表，嵌入外部样式表，链接外部样式表，
            23 id，class
            2   分析：
            想要去掉元素的某一条边框，写法有3种
            第13章 列表样式
            参考答案：1A
            2    实现代码如下：
            <!DOCTYPE html>
            <html>
            <head>
               <meta charset="utf-8" />
               <title></title>
               <style type="text/css">
                  ul{list-style-type:none;}
                  a{color:pink;text-decoration:none;}
               </style>
            </head>
            <body>
            <ul>
               <li><a href="www.baidu.com" target="_blank">Top1：百度</a></li>
               <li><a href="www.taobao.com" target="_blank">Top2：淘宝</a></li>
               <li><a href="www.sina.com" target="_blank">Top3：新浪</a></li>
               <li><a href="www.163.com" target="_blank">Top4：网易</a></li>
               <li><a href="www.sohu.com" target="_blank">Top5：搜狐</a></li>
            </ul>
            </body>
            </html>

            第14章 表格样式
            参考答案：1B, 2C, 3B，4C

            第15章 图片样式
            参考答案：1B2C
            2分析：
            A中，img元素虽然不是块元素，但是它却是可以设置width和height这两个属性的。
            B中，vertical-align属性定义周围的行内元素或文本相对于该元素的垂直方式，并不能实现图片在div元素中垂直居中；
            D中，应该使用float属性；

            第16章 背景样式
            参考答案：1A,2A
            1分析：
            color设置的是文本颜色，background-color设置的是背景颜色。根据英文意思，也很容易区分；
            2 分析：
            A中，默认情况下，背景图片是同时在X轴和Y轴两个方向平铺的；

            3   实现代码如下：
            <!DOCTYPE html>
            <html>
            <head>
               <meta charset="utf-8" />
               <title></title>
               <style type="text/css">
                  body
                  {
                     background-image:url(img/pic.png);
                  }
               </style>
            </head>
            <body>
            </body>
            </html>
            第17章  超链接样式
            参考答案：1C,2A，3D，4A
            4分析：
            B中，自定义鼠标样式使用的图片后缀名应该是.cur；
            C中，:hover伪类可以用于所有元素；
            D中，在实际开发中，我们一般只会定义2种状态：鼠标未访问时状态和鼠标经过时状态；
            5  实现代码如下：
            <!DOCTYPE html>
            <html>
            <head>
               <meta charset="utf-8" />
               <title></title>
               <style type="text/css">
                  a
                  {
                     text-decoration:none;
                     color:red;
                  }
                  a:hover
                  {
                     text-decoration:underline;
                     color:blue;
                  }
               </style>
            </head>
            <body>
            <a href="http://www.lvyestudy.com" target="_blank">绿叶学习网</a>
            </body>
            </html>
            第18章 盒子模型
            一、单选题
            1、下面哪个属性用于定义外边距？（  ）
            A. content          B.padding          C.border           D.margin
            2、下面有关CSS盒子模型的说法中，正确的是（   ）。
            A. margin不属于元素的一部分，因为它不在边框内部
            B. padding又称为“补白”，指的是边框到“父元素”或“兄弟元素”之间的那一部分
            C. “margin:20px 40px 60px 80px;”表示margin-top为20px，margin-left为40px，margin-bottom为60px，margin-right为80px。
            D. width和height只是针对内容区（content）而言的，不包括内边距（padding）。
            分析：
            A中，margin虽然不在边框内部，但是它属于元素的一部分；
            B中，padding指的是边框到内容区之间的那一部分，而margin指的才是边框到“父元素”或“兄弟元素”之间的那一部分；
            C中，margin:20px 40px 60px 80px;”表示margin-top为20px，margin-right为40px，margin-bottom为60px，margin-left为80px，按照顺时针方向来理解；
            3、如果一个div元素的上内边距和下内边距都是20px，左内边距是30px，右内边距是40px，正确的写法是（   ）。
            A. padding:20px 40px 30px;                 B. padding:20px 40px 20px 30px;
            B.padding:20px 30px 40px;                  D.padding:40px 20px 30px 20px;
            4、对于“margin:20px 40px;”，下面说法正确的是（   ）。
            A. margin-top是20px，margin-right是40px，margin-bottom和margin-left都是0
            B. margin-top是20px，margin-bottom是40px，margin-left和margin-right都是0
            C. margin-top和margin-bottom都是20px，margin-left和margin-right都是40px
            D. margin-top和margin-bottom都是40px，margin-left和margin-right都是20px
            5、默认情况下，（   ）元素设置width和height可以生效。
            A. div             B.span            C.strong             D.em
            第19章 浮动与定位布局
            一、单选题
            1、如果想要实现文本环绕着图片，最好的解决方法是（   ）。
            A. 浮动布局            B.定位布局          C.表格布局         D.响应式布局
            2、在CSS中，“clear:both;”的作用是（   ）。
            A. 清除该元素的所有样式
            B. 清除该元素的父元素的所有样式
            C. 清除该元素的兄弟元素浮动之后带来的影响
            D. 清除该元素的父元素浮动之后带来的影响
            3、下面有关浮动的说法中，不正确的是（   ）。
            A. 浮动和定位都是使得元素脱离文档流来实现布局的
            B. 如果想要实现多列布局，最好的方式是使用定位布局
            C. 浮动是魔鬼，如果控制不好的话，会造成页面布局混乱
            D. 想要清除浮动，更多使用的是“clear:both;”，而不是“clear:left;”或“clear:right;”来实现
            4、我们可以定义position属性值为（  ），从而来实现元素的相对定位。
            A. fixed       B. relative       C.absolute         D.static
            5、下面哪个属性不会让div元素脱离文档流？（   ）
            A. position:fixed;                  B.position:relative;
            C. position:absolute                D.float:left;
            6、默认情况下，以下关于定位布局的说法不正确的是（   ）。
            A. 固定定位元素的位置是相对浏览器四条边
            B. 相对定位元素的位置是相对于原始位置
            C. 绝对定位元素的位置是相对于原始位置
            D. position属性的默认值是static
            分析：
            C中，默认情况下，绝对定位元素的位置是相对于浏览器四条边；
            7、下面有关定位布局，说法不正确的是（   ）。
            A. 想要实现相对定位或绝对定位，我们只需要用到top、right、bottom、left的其中2个就可以了
            B. 绝对定位可以让元素完全脱离文档流，元素不会占据原来的位置
            C. 现在的前端开发不再使用表格布局，而是使用浮动布局和定位布局
            D. 在实际开发中，优先使用定位布局。如果实现不了，再考虑浮动布局
            二、编程题
            8、使用浮动布局来实现下图所示的页面布局效果，其中各个元素之间的间距是10px。下面只给出必要的尺寸，也就是说有些尺寸需要我们自己计算的。在实际开发中，计算尺寸是家常便饭，所以这里我们自己试一下。

            第18章 盒子模型
            参考答案：1D,2D,3B,4C,5A

            第19章 浮动与定位布局
            参考答案：1A、2C、3B、4B、5B、6C、7D
            2、分析：“clear:both;”清除的是浮动，并不是样式。“clear:both;”清除的是兄弟元素的浮动，并不会清除父元素的浮动
            3、分析：    B中，如果想要实现多列布局，最好的方式是使用浮动布局；
            7、分析：    在实际开发中，优先使用浮动布局。如果实现不了，再考虑定位布局。因为定位布局大多数情况会使得元素完全脱离原来的位置，使得布局不可控；
            8、    实现代码如下：
            <!DOCTYPE html>
            <html>
            <head>
               <meta charset="utf-8" />
               <title></title>
               <style type="text/css">
                  #wrapper
                  {
                     width:800px;
                     height:600px;
                  }
                  #header,#footer
                  {
                     height:98px;
                     background-color:lightskyblue;
                  }
                  .main-left,.main-right
                  {
                     height:380px;
                     margin-top:10px;
                     margin-bottom:10px;
                     background-color:hotpink;
                  }
                  .main-left
                  {
                     float:left;
                     width:595px;
                  }
                  .main-right
                  {
                     float:right;
                     width:195px;
                  }
                  .clear{clear:both;}
               </style>
            </head>
            <body>
            <div id="wrapper">
               <div id="header"></div>
               <div id="main">
                  <div class="main-left"></div>
                  <div class="main-right"></div>
                  <div class="clear"></div>
               </div>
               <div id="footer"></div>
            </div>
            </body>
            </html>
            第二部分 项目练习题参考答案

            项目1 网页制作基础知识

            一、	填空题（2‘*5）
            1、网站由网页构成，并且根据功能的不同，网页又有____和动态网页之分。
            2、Web标准是一系列标准的集合，主要包括结构、____和____。
            3、HTML中文译为________________，主要是通过HTML标签对网页中的文本、图片、声音等内容进行描述。
            4、在网页名词中，_________是Internet提供的一种网页浏览服务。
            5、在网站建设中，HTML用于搭建页面结构，CSS用于设置页面样式，__________用于为页面添加动态效果。
            二、	判断题（2‘*10）
            1、因为静态网页的访问速度快，所以现在互联网上的大部分网站都是由静态网页组成的。
            2、网页中也可以包含音频、视频以及Flash动画。
            3、“HTTP”是一种详细规定了浏览器和万维网服务器之间互相通信的规则。(   )
            4、URL（英文Uniform Resource Locator的缩写）中文译为“统一资源定位符”。URL其实就是Web地址，俗称“网址”。(     )
            5、在Internet上域名与IP地址之间并不是对应的。(     )
            6、Firebug是IE浏览器中常用的一个插件。（  ）
            7、在网站建设中，JavaScript用于搭建页面结构。(     )
            8、Hbuilder工具能编写HTML代码。(     )
            9、在Hbuilder中，使用快捷键Ctrl+S，即可完成文件的保存。 (     )
            10、所有的浏览器对同一个CSS样式的解析都相同，因此页面在不同浏览器下的显示效果完全一样。(    )
            三、	选择题（2*10）
            1、在Dreamweaver中，使用主浏览器预览网页的快捷键是（   ）。
            A、Ctrl+S       B、F12        C、F5       D、Ctrl+F12
            2、使用内嵌式添加CSS样式，CSS样式需要写在(       )。
            A、<title></title>标签之间
            B、<head></head>标签之间
            C、<body></body>标签之间
            D、<style></style>标签之间
            3、对JavaScript语言描述，下列选项正确的是（    ）。
            A、JavaScript是Web页面中的一种脚本语言文字。
            B、JavaScript用于为页面添加动态效果。
            C、JavaScript可以替代html和css。
            D、JavaScript语言的前身是LiveScript语言。
            4、下面选项中，属于网页构成元素的是（    ）。
            A、	音频		B、	视频		C、	文字		D、	psd图像
            5、浏览器是网页运行的平台，下列属于网页制作中常用浏览器的是（  ）。
            A、IE    B、谷歌    C、火狐   D、搜狗
            6、在Dreamweaer中，使用次浏览器预览网页的快捷键是（    ）。
            A、f9    B、f10    C、f12   D、ctrl+f12
            7、在HTML中，网页要显示的主体内容应放置在（    ）。
            A、<title></title>标签之间
            B、<head></head>标签之间
            C、<body></body>标签之间
            D、HTML中的任意位置
            8、下列选项中的术语名词，属于网页术语的是( )。
            A、WEB		B、HTTP		C、DNS		D、IOS
            9、下面的选项中，关于Web标准说法正确的是（     ）。
            A、Web标准只要包括HTML标准。
            B、Web标准是由浏览器的各大厂商联合制定的。
            C、Web标准并不是某一个标准，而是一系列标准的集合。
            D、Web标准主要包括结构标准、表现标准和行为标准三个方面。
            10、下列选项中属于Web标准构成部分的是(     )。
            A、结构标准  B、表现标准  C、行为标准  D、以上说法均正确

            一、填空题参考答案
            1 静态网页
            答案说明	网站由网页构成，网页有静态和动态之分。所谓静态网页是指用户无论何时何地访问，网页都会显示固定的信息，除非网页源代码被重新修改上传。静态网页更新不方便，但是访问速度快。而动态网页显示的内容则会随着用户操作和时间的不同而变化，这是因为动态网页可以和服务器数据库进行实时的数据交换。
            2 表现 行为
            答案说明	Web标准并不是某一个标准，而是一系列标准的集合，主要包括结构（Structure）、表现（Presentation）和行为（Behavior）三个方面。
            3 答案	超文本标签语言
            答案说明	HTML（英文Hyper Text Markup Language的缩写）中文译为“超文本标签语言”，主要是通过HTML标签对网页中的文本、图片、声音等内容进行描述。
            4 答案	WWW
            答案说明	WWW（英文World Wide Web的缩写）中文译为“万维网”。但WWW不是网络，也不代表Internet，它只是Internet提供的一种服务——网页浏览服务
            5 JavaScript
            答案说明	考察对JavaScript的理解
            二、判断题参考答案
            1答案	错
            答案说明	现在互联网上的大部分网站都是由静态网页和动态网页混合组成的，两者各有千秋，用户在开发网站时可根据需求酌情采用。
            2答案	对
            答案说明	网页主要由文字、图像和超链接等元素构成。当然，除了这些元素，网页中还可以包含音频、视频以及Flash等。
            3答案	对
            答案说明	HTTP (英文Hypertext transfer protocol的缩写) 中文译为超文本传输协议。它是一种详细规定了浏览器和万维网服务器之间互相通信的规则。
            4答案	对
            答案说明	URL（英文Uniform Resource Locator的缩写）中文译为“统一资源定位符”。URL其实就是Web地址，俗称“网址”。
            5答案	错
            答案说明	DNS（英文Domain Name System的缩写）是域名解析系统。在Internet上域名与IP地址之间是一一对应的。
            6答案	错
            答案说明	Firebug是火狐浏览器下的一款开发插件，属于火狐强力推荐的插件之一，它集HTML查看和编辑、Javascript控制台、网络状况监视器于一体，是开发JavaScript、CSS、HTML和Ajax的得力助手。
            7答案	错
            答案说明	在网站建设中，HTML用于搭建页面结构，CSS用于设置页面样式，而JavaScript则用于为页面添加动态效果。
            8答案	对
            答案说明	网页制作过程中，为了开发方便，通常我们会选择一些较便捷的工具，如HBuilder、Editplus、notepad++、sublime、Dreamweaver等。实际工作中，最常用的网页制作工具是Dreamweaver。Dreamweaver可以编写HTM代码，CSS代码，JavaScript代码。
            9答案	对
            答案说明	在Dreamweaver中制作网页，在菜单栏中选择【文件】→【保存】选项，或使用快捷键Ctrl+S，即可完成文件的保存。
            10答案	错
            答案说明	不同的浏览器对同一个CSS样式有不同的解析，这样就导致了同样的页面在不同浏览器下的显示效果可能不同。
            三、选择题参考答案
            1答案	B
            答案说明	在Dreamweaver中，使用主浏览器预览网页的快捷键是F12，一般把IE浏览器或谷歌浏览器设为次浏览器，快捷键Ctrl+F12。
            2答案	D
            答案说明	<title>与</title>标签之间，输入HTML文档的标题，在<body>与</body>标签之间添加网页要显示的主体内容, CSS样式写在<style></style>标签内。
            3答案	ABD
            答案说明	JavaScript是Web页面中的一种脚本语言，在网站建设中，HTML用于搭建页面结构，CSS用于设置页面样式，
            而JavaScript则用于为页面添加动态效果。JavaScript语言的前身是LiveScript语言，
            最初由Netscape（网景公司）的Brendan Eich（瑞登•艾克）设计，后来Netscape为了营销考虑，
            与Sun微系统达成协议，将其改名为JavaScript。
            4答案	ABC
            答案说明	网页主要由文字、图像和超链接等元素构成。当然，除了这些元素，网页中还可以包含音频、视频以及Flash等， pad格式不能在网上直接显示，所以不能选。
            5答案	ABC
            答案说明	IE、火狐和谷歌是目前互联网上的三大浏览器，其他常用的浏览器还有苹果的Safari浏览器和欧朋浏览器等。对于一般的网站，只要兼容IE浏览器、火狐浏览器和谷歌浏览器，就能满足绝大多数用户的需求。
            6答案	D
            答案说明	使用次浏览器预览网页的快捷键是【Ctrl+ F12】
            7答案	C
            答案说明	<title>与</title>标签之间，输入HTML文档的标题，
            在<body>与</body>标签之间添加网页要显示的主体内容。
            8答案	ABC
            答案说明	WEB 就是我们说网页，它是一系列技术的复合总称（包括网站的前台布局、后台程序、美工、数据库开发等），
            我们称它为网页，HTTP (英文Hypertext transfer protocol的缩写) 中文译为超文本传输协议，
            DNS （英文Domain Name System的缩写）是域名解析系统。 IOS是苹果设备的主开发语言并不是网页术语。
            9答案	CD
            答案说明	Web标准是由W3C与其他标准化组织共同制定的，它并不是某一个标准，而是一系列标准的集合，
            主要包括结构（Structure）、表现（Presentation）和行为（Behavior）三个方面。
            10答案	ABCD
            答案说明	Web标准并不是某一个标准，而是一系列标准的集合，主要包括结构（Structure）、
            表现（Presentation）和行为（Behavior）三个方面。




            项目2 “博客”页面制作参考答案
            一、填空题（2‘*5）
            1、网页的根标签是<html></html>，主体标签是_________，标题标签是_________。
            2、	_________标签位于文档的最前面，用于向浏览器说明当前文档使用哪种HTML或XHTML标准规范。
            3、网页当中的常见图片格式有JPEG格式，______格式和_______格式。
            4、	<font>标签的____________属性可以设置文本的颜色。
               5、	<img />标签表示一个图像信息，它有一个必须要指定的_____属性，用来指定图片路径。
               填空题参考答案
               1答案	<body></body>  <title></title>
               答案说明	无
               2答案	<!DOCTYPE>
               答案说明	<!DOCTYPE> 标签位于文档的最前面，用于向浏览器说明当前文档使用哪种 HTML 或 XHTML 标准规范，如《网页设计与制作（HTML+CSS）》这本书中使用的是Dreamweaver默认的XHTML1.0过渡型XHTML文档。
               3答案	png, gif
               答案说明	目前，网页上常用的图像格式主要有GIF、JPEG和PNG三种。
               4答案	color
               答案说明	无
               5答案	src
               答案说明	src属性用于指定图像文件的路径和文件名，它是img标签的必需属性。

               二、判断题（2‘*10）
               1、一个HTML文档只能含有一对<body>标签，且<body>标签必须在<html>标签内。（ ）
               2、一个HTML文档可以含有多对<head>标签。（ ）
                  3、<hr />为单标签，用于定义一条水平线。（ ）
                  4、<!DOCTYPE>标签和浏览器的兼容性无关，为了代码简洁，可以删掉。(  )
                  5、设置了<p>标签的文本，在一个段落中会根据浏览器窗口的大小自动换行。(  )
                     6、在HTML中，标签可以拥有多个属性。（ ）
                     7、在标签的嵌套过程中，必须先结束最靠近内容的标签，再按照由外及内的顺序依次关闭标签。（ ）
                     8、图像文件和html文件位于同一文件夹，相对路径为<img src="logo.gif" />。（  ）
                     9、在特殊字符中，<sub>用来表示上标。（ ）
                        10、在特殊字符中，“&lt;”用来表示小于号，“&gt;”用来表示大于号。（ ）
                        判断题参考答案
                        1答案	对
                        答案说明	一个HTML文档只能含有一对<body>标签，且<body>标签必须在<html>标签内，位于<head>头部标签之后，与<head>标签是并列关系。
                  2答案	错
                  答案说明	一个HTML文档只能含有一对<head>标签，绝大多数文档头部包含的数据都不会真正作为内容显示在页面中。
                     3答案	对
                     答案说明	单标签也称空标签，是指用一个标签符号即可完整地描述某个功能的标签。其中<hr />为单标签，用于定义一条水平线。
                     4答案	错
                     答案说明	<!DOCTYPE>标签和浏览器的兼容性相关，删除<!DOCTYPE>，就是把如何展示HTML页面的权利交给浏览器。这时，IE6，IE7，IE8，Firefox2，Firefox3，Chrome，有多少种浏览器，页面就有可能有多少种显示效果，这是不被允许的。
                     5答案	对
                     答案说明	<p>是HTML文档中最常见的标签，默认情况下，文本在一个段落中会根据浏览器窗口的大小自动换行。
                        6答案	对
                        答案说明	标签可以拥有多个属性，必须写在开始标签中，位于标签名后面。
                        7答案	错
                        答案说明	在标签的嵌套过程中，必须先结束最靠近内容的标签，再按照由内及外的顺序依次关闭标签。
                        8答案	对
                        答案说明	使用相对路径时，图像文件和html文件位于同一文件夹：只需输入图像文件的名称即可，如<img src="logo.gif" />。
                        9答案	错
                        答案说明	在特殊字符中，<sub>用来表示下标，<sup>用来表示上标。
                           10答案	正确
                           答案说明	在特殊字符中，“&lt;”用来表示小于号，“&gt;”用来表示大于号。

                           三、¬选择题（2‘*10）
                           1、下列标签中，用于定义HTML文档所要显示内容的是（   ）。
                           A、 <head></head>		B、 <body></body>
               C、 <html></html>		D、 <title></title>
               2、位于HTML文档的最前面的标签是（    ）。
               A、 <!DOCTYPE>			B、 <head></head>
               C、 <title></title>		D、 <html></html>
               3、下列选项中，说法正确的是（    ）。
               A、 在HTML中还有一种特殊的标签——注释标签 	B、标签分为单标签和双标签
               C、 <h2/> 二级标题是一个单标签			D、 <p></p>是一个双标签
               4、在HTML中，表示内嵌CSS样式的标签是（    ）。
               A、<title>   B、<style>    C、<head>   D、<meta>
                  5、<font>标签可以设置的属性有（    ）。
                  A、color    B、align    C、size   D、font-family
                  6、下列属性中，用于设置鼠标悬停时图像的提示文字的是哪一项？（    ）
                  A、title    B、alt    C、width   D、height
                  7、下面的选项中，支持透明的图像是哪一项？（    ）。
                  A、jpg格式    B、gif格式    C、psd格式   D、png格式
                  8、下列关于特殊字符的说法错误的是（   ）
                  A、特殊字符的代码前缀为&   		B、可以通过菜单栏直接插入相应特殊字符的代码
                  C、转义序列各字符间可以有空格   	D、转义序列必须以分号结束
                  9、下列标签中，用来设置文本为粗体的是（   ）
                  A、<u></u>				B、<del></del>
                  C、<strong></strong> 	D、<b></b>
                  10、<img />标签链接图片路径的属性是（    ）。
                  A、src    B、alt    C、width   D、height

                  选择题参考答案
                  1答案	B
                  答案说明	<body>标签用于定义HTML文档所要显示的内容，也称为主体标签。浏览器中显示的所有文本、图像、音频和视频等信息都必须位于<body>标签内，<body>标签中的信息才是最终展示给用户看的。
                  2答案	A
                  答案说明	<!DOCTYPE> 标签位于文档的最前面，用于向浏览器说明当前文档使用哪种 HTML 或 XHTML 标准规范，如《网页设计与制作（HTML+CSS）》这本书中使用的是Dreamweaver默认的XHTML1.0过渡型XHTML文档。
                  3答案	ABD
                  答案说明	在HTML中还有一种特殊的标签——注释标签<!--这是一段注释-->， 在HTML中标签分为单标签和双标签，其中 <p></p>是一个双标签，同样<h2></h2>也是一个双标签。
                  4答案	B
                  答案说明	在HTML中使用style标签表示使用内嵌式的CSS样式。
                  5答案	AC
                  答案说明	<font>标签常用的属性有3个分别是color为文字颜色控制属性，size为字号控制属性，face为字体控制属性。
                  6答案	A
                  答案说明	用于设置鼠标悬停时图像的提示文字的属性是title属性。
                  7答案	BD
                  答案说明	在这4个选项中，只有gif和png图像支持透明。
                  8答案	C
                  答案说明	特殊字符的代码通常由前缀“&”、字符名称和后缀为英文状态下的“;”组成。在网页中使用这些特殊字符时只需输入相应的代码替代即可。另外，在Dreamweaver中，还可以通过菜单栏中的【插入】→【HTML】→【特殊字符】选项直接插入相应特殊字符的代码。另外，转义序列各字符间不能有空格，并且转义序列必须以分号结束。
                  9答案	CD
                  答案说明	<u></u>表示下画线，<del></del>表示删除线，<strong></strong>和<b></b>表示粗体。
                  10答案	A
                  答案说明	src属性用于指定图像文件的路径和文件名，他是img标签的必需属性。




```

---