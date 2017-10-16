 
 
 #1.大标题
 --------------
 
 在文本下方加上 ====== 即是大标题 <br />
 例子:
 
 &nbsp;&nbsp;&nbsp;我是大标题
 ============
 <br />
 
 
 #2.中标题
 
 在文本下方加上 ====== 即是中标题 <br />
 例子：
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;我是中标题
 ---------------
 
 <br />
 <br />
 
 #3.直接变成一条横线
 在上方没有文字的情况下直接输入--------- <br //>
 例子: <br />
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 这个横线↓↓↓
 
 -----------------------------
 
 <br />
 
 #4.既要文字也要横线
 在文字和横线的中间打一个空行 <br />
 例： <br />
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 这是文字
 
 ---------------------
 
 #4.标题：
 ---------------
 #一级标题
 ##二级标题
 ###三级标题
 ####四级标题
 #####五级标题
 ######六级标题
 <br />
 
 
 #5.普通文本
 ---------------
 
 这段文字就是普通文本<br>
 这段文字就是普通文本<br>
 这段文字就是普通文本<br>
 这段文字就是普通文本<br>
 这段文字就是普通文本<br>
 注意：  
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 `回车换行是没有用的，需要在文字后方加上 br 或者 html 语言  `
 

 <br /> 
 <br />
 
 #6.超链接
 ---------------
 直接输入链接的url,显示出来后会自动变成可链接形式
 <br />
 例：
 <br />
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 https://baidu.com
 
 <br />
 <br />
 
 #7.文字超链接
 ----------------
 
 1.给一段文字加上一个超链接格式  
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
 格式：
 <br />
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 ` ![标识](url) 例(1)`
 <br />
 <br />
 2.给一段文字加上一个超链接格式并添加悬停效果   
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
 格式:
 <br />
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 ` ![标识](url "悬停显示" (例2)) `
 
 例子：
 
 1. [lcz1120的博客](https://github.com/lcz1120)

 2. [鼠标移入到此处悬停显示](https://github.com/lcz1120 "lcz1120的博客")
 
 <br />
 <br />
 <br />

#8.单行文本
------------------

 使用两个Tab符实现单行文本
 
 例子：
 
    这是单行文本

<br />
<br />
<br />

#9.多行文本
-----------------

在每行加上两个tab实现多行文本
<br />
例：
    
    文本1
    文本2
    文本3

<br />
<br />
<br />

#10.部分文字高亮
----------------

使用``把要高亮的文字包起来

例：

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 我是普通文字         &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
`我是高亮文字  `
 
 <br />
 <br />
 <br />
 
 #11.圆点符
 ---------------
 
 在文字前加个 * +空格  (例1) <br />
 
 此外还有二级圆点和三级圆点，就是多加一个Tab (例2)
 
 注意：

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 `*后面必须跟加空格`
 
 例1:

* 名称：随心
* 别名：suixin
* github：[lcz1120](https://github.com/lcz1120 "lcz1120的博客")
 
例2.

 * 名称：随心
    * 别名：suixin
        * github：[lcz1120](https://github.com/lcz1120 "lcz1120的博客")
 
<br />
<br />
<br />

#12.缩进
--------------------

在文本前方加个 > 符号来表示缩进
需要缩进多少个字符就加多少个 > 

例：
>数据结构
>>树
>>>二叉树
>>>>平衡二叉树
>>>>>满二叉树

#13.插入图片
--------------------

######一、图片来源于网络
<br />
<br />
写法：

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
`` 1. ![](url) (例1) ``

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
`` 2. ![标志性信息](url) (例2)``

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
`` 3. ![标志性信息](url "悬停显示") (例3)``    

注意：

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 ``如果不加 叹号! 就会变成普通文本``
 
 用法：

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 `叹号! + 方括号[baidu] + 括号(url) `
 
 例子：
 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 1.无标志性信息
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![](https://baidu.com/img/bdlogo.gif)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
2.有标志性信息

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![baidu](https://baidu.com/img/bdlogo.gif)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
3.悬停显示

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![baidu](https://baidu.com/img/bdlogo.gif "万事找度娘~( • ̀ω•́ ) ✧")
 
 
 ######二、图片来源于github
 ------------------------------
 
 用法：
 <br />
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
     与插入图片的用法是一致的，唯一不同的就是url的写法不同 (例1)
    
 写法：
 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    `https://github.com/你的用户名/你的项目名/raw/分支名/存放图片的文件夹/该文件夹下的图片`

 例贼儿：
 
 ![background](https://github.com/lcz1120/lcz1120.github.io/raw/master/images/avatar.jpg "background")
 
 ######三、图片加上超链接
 ------------------------------
 
 写法：
 
   [![baidu]](http://baidu.com)
   [baidu]:http://www.baidu.com/img/bdlogo.gif "我是万能的~( • ̀ω•́ )"
   
  注意：
  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;
  `注意上下文中的baidu是自己起的标识名称，可以随意，但是一定要保证上下两行的 **标识** 是一样的`
  
