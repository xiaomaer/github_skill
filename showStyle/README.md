设置README.md文件格式。

### 横线
* 实线：
  
  ===
* 虚线：
  
  ----
  ****
  _____

### 标题
大标题样式
===

中标题样式
----

#一级标题样式
##二级标题样式
###三级标题样式
#### 四级标题样式
##### 五级标题样式
###### 六级标题样式

###文字
#### 普通文字 
直接输入的文字就是普通文本。

####单行文字  
    我是单行文字
 
####多行文字  
    我是多行文字的第一行
    我是多行文字的第二行
    我是多行文字的第三行

#### 部分文字高亮 
我是`部分高亮文字哦`，哈哈哈

####删除线
~~在文字上添加删除线~~

####粗体
**这是文字粗体格式**

####斜体
*这是文字斜体格式*

####换行
行1，在后面输入两个空格进行换行  
行2

####显示空格
我是　　　空格。把输入法切换到全角模式，输入空格，才会显示哦

###文本链接
####链接到外部URL
* 普通效果  
[小马的博客](http://y.dobit.top/)
* 鼠标悬停显示效果  
[小马的博客](http://y.dobit.top/ "悬停显示")  

####链接到仓库的url
[相对地址](../README.md)

[绝对地址](https://github.com/xiaomaer/github_skill/)

####锚
[回到顶部](#横线)

###符号列表
####圆点列表
* 列表1
  * 列表1.1
    * 列表1.1.1
* 列表2
  * 列表2.1
    * 列表2.1.1

####数字列表
#####普通数字列表
1. 列表1
2. 列表2
3. 列表3
  * 列表3.1
  * 列表3.2

#####自动增加数字列表
1. 列表1
* 列表2
* 列表3

#####多级数字列表
1. 列表1
2. 列表2
3. 列表3
  1. 列表3.1
  2. 列表3.2
    1. 列表3.2.1

####复选框列表

###文本缩进
>Once you are happy with your document, you can publish it on different websites directly from StackEdit. As for now, StackEdit can publish on Blogger, Dropbox, Gist, GitHub, Google Drive, Tumblr, WordPress and on any SSH server.

####多级缩进
>第一级，一个“>”符号
>>第二级，两个">"符号
>>> 第三级，三个“>”符号
>>>> 第四级，四个“>”符号，依次类推 

###插入图片
####插入来自网络的图片
![网络图片无悬停](http://7xj89g.com1.z0.glb.clouddn.com/demo3.jpg?imageView2/2/w/400/q/50)
![网络图片有悬停](http://7xj89g.com1.z0.glb.clouddn.com/demo2.jpg?imageView2/2/w/400/q/50 "我是悬停信息")

####插入来自仓库的图片
![来自仓库的图片绝对地址](https://github.com/xiaomaer/github_skill/blob/master/1.gif "绝对地址显示")
![来自仓库的图片相对地址](../2.gif "相对地址显示")

####给图片加上链接
[![myblog]](http://y.dobit.top/)  
[myblog]:http://7xj89g.com1.z0.glb.clouddn.com/demo2.jpg?imageView2/2/w/400/q/50 "悬停文字"  

###代码高亮
```java
public static void main(String[]args){} //Java
```
```c
int main(int argc, char *argv[]) //C
```
```javascript
document.getElementById("myH1").innerHTML="Welcome to my Homepage"; //javascipt
```

###表格
####普通表格
|Item     | Value|
|-------- | -----|
|Computer | $1600|
|Phone    | $12  |
|Pipe     | $1   |

####表格某列单元格文本对齐方式
| 左对齐   | 右对齐| 居中  |
| :------- | ----: | :---: |
| Computer | $1600 |  5    |
| Phone    | $12   |  12   |
| Pipe     | $1    |  234  |

###添加表情
:sparkling_heart:
:green_heart:
:star:
