###Welcome to use MarkDown
#### 主要实现 链接 图片 引用 代码块  
#### 1.链接
- 外部链接

[百度](http://www.baidu.com)

##### 内嵌式链接
- 链接仓库的其他文件  在同一仓库 直接写相对路径
[demo1](demo1.md)

- 链接本文档的其它部分
[代码块](demo2.md#代码块)
 

##### 引用式链接
- 可以在一个地方定义好变量，每次要用到时，就去引用它  
[百度]  
[百度][baidu] 
[demo1]  
[代码块]  


#### 2.图片到的链接
![alt](url text)  
- alt:如果图片不能正常显示时，显示的文字内容 
- url:图片的地址 与text之间有空格
- text: 当鼠标放在图片上显示的内容
![baidu](https://www.baidu.com/img/bd_logo1.png "百度网站")  

- 外部图片

![baidu](https://www.baidu.com/img/bd_logo1.png "百度网站")  

- 仓库内部图片

![](images/iPadmini5.jpg "iPadMini5") 
 
- 图片的引用式链接

![baidu]
#### 3.引用

- 引用其他文字 用">"加上空格来实现

> 人们还往往把真理和错误混在一起去教人,而坚持的却是错误。

--歌德

- 多次引用。
>啦啦>拉拉啊> 多重引用

#### 代码块
- 行内代码

声明变量` var a=10`,打印变量 `console.log`函数调用
- 块代码 使用"```"来实现
```javascript
var a=10;
```

这里是引用要用到的链接  
<<<<<<< HEAD
[百度]: http://www.baidu.com
[baidu]: http://www.baidu.com
[demo1]: demo1.md  
[代码块]: demo2.md#代码块    
![baidu]: https://www.baidu.com/img/bd_logo1.png "百度网站"  
=======
[百度]: http://www.baidu.com  

[baidu]: http://www.baidu.com 

[demo1]: demo1.md    

[代码块]: demo2.md#代码块    
>>>>>>> 13bdc2a41e4863a1c122a0a79fb2b349cb9a8b11
