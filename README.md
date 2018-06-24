# test
##学习markdown

####1.使用git pull提示refusing to merge unrelated histories
    创建了一个origin，两个人分别clone
    分别做完全不同的提交
    第一个人git push成功
    第二个人在执行git pull的时候,提示
    fatal: refusing to merge unrelated histories

解决方法:
git pull --allow-unrelated-histories

####2.cat README.md
可以查看README.md文件的内容

####3.ls -l
可以查看文件列表

####4.git log --oneline
查看提交列表

段落后面加两个空格
斜体   *git pull --allow-unrelated-histories*   
斜体   _git pull --allow-unrelated-histories_

粗体   **userrname:lingyixyw**  
粗体   __userrname:lingyixyw__   
粗斜体    ***code:xyw***  
粗斜体    ___code:xyw___  

删除线    ~~查看提交列表~~  
删除线    ~~查看提交列表~~

##无序列表

我的个人信息  
* name  
* QQ   

等价写法  

我的个人信息  
- name  
  - name
  - name
    - name
- QQ 

##有序列表

我的个人信息  
1. name  
  1. name
  2. name
  3. name
2. QQ 



##链接  

###内嵌式链接  

- 外部链接：[百度](http://www.baidu.com)
- 内部链接1，链接仓库的其他文件：[a1](a1.md)
- 内部链接2，链接本文档的其它部分： [代码块 demo](README.md#代码块 demo)

###引用式链接

- 外部链接：[百度]
- 外部链接：[百度][baidu]
- 内部链接1，链接仓库的其他文件：[a1]
- 内部链接2，链接本文档的其它部分： [代码块 demo]

##图片  

- 图片的 MarkDown 语法
    ![alt](url text)
- 外部图片 demo
![baidu](https://www.baidu.com/img/bd_logo1.png "百度网站")
- 仓库内的图片 demo
![](images/img.png)

图片的引用式链接：

- 外部图片 demo
![baidu][baidu_logo]
- 仓库内的图片 demo
![][img_png]

##引用  

> 这是一个引文。

出自《出处》


多重引用

>>>这是多重引文。

##代码块 demo

- 行内代码

这个代码中用来声明变量是`var a = 10`，打印变量内容是`console.log `函数的调用。


- 块式代码

```javascript
var a = 10;
console.log(a);
```

无高亮
    var a = 10;
    console.log(a);



##水平分隔线

    <hr> Horizontal Rule
    
---

    <hr> Horizontal Rule
    
***

    <hr> Horizontal Rule
    
___


<!---  下面是本文档中用到的链接 -->

[百度]: http://www.baidu.com
[baidu]: http://www.baidu.com
[a1]: a1.md
[代码块 demo]: README.md#代码块 demo
[baidu_logo]: https://www.baidu.com/img/bd_logo1.png
[img_png]: images/img.png
