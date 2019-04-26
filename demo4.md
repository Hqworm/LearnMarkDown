###Welcome to use MarkDown
## 混合强调样式
### 1.基本强调样式
- **加粗**  ....  __加粗__
- *斜体* ....._斜体_
- ~~线删除~~
### 2.混合强调样式
- ***加粗倾斜***
- **~~加粗删除~~**
- *~~斜体删除~~*
- ***~~加粗倾斜删除~~***

## 混合 图片链接

### 1.基本文字链接
- [链接文字](URL)    列如----> [baidu](http://www.baidu.com)

- 基本图片链接：  ![alt](url text) 

![baidu](https://www.baidu.com/img/bd_log1.png)

- **图片链接**
[![](https://www.baidu.com/img/bd_log1.png)](https://www.baidu.com)

[![][baidu_logo]][baidu]  

#### 引用链接的问题top
- 基本引用链接的用法   
[baidu] 

[百度][baidu] 
 
[百度官网][baidu] 起了别名

### 多级列表问题
- item1
  - item1.1
  - item1.2
- item2
- item3
- item4

1. item1
  1. item1.1
  2. item1.2
2. item2
3. item3
4. item4

打断列表在列表之间加入文字可以打断，空行不行。
1. item1
  1. item1.1
  2. item1.2
2. item2

啦啦啦打断啦  需要文字段落哟，文字前后有空格

3. item3
4. item4  


如果把打断的续上，则正文字前面呢缩进空格*4，--把他看做列表的子列表

1. item1
  1. item1.1
  2. item1.2
2. item2
    打断续上了
3. item3
4. item4 

<!--以下是本文中的使用到的链接-->  

[baidu]: http://www.baidu.com

[baidu_logo]: http://www.baidu.com/img/bd_logo1.png
