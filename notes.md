# Markdown语法

Source: 
1. https://zhuanlan.zhihu.com/p/86516807
2. https://blog.csdn.net/ZM_Yang/article/details/105617607
3. https://support.typora.io/Markdown-Reference/
4. https://www.markdownguide.org/cheat-sheet/

其实常用的就那么几个：
1. 标题；
2. 段落；
3. 列表；
4. 图片；
5. 链接；
6. 表格；
7. 引用；
8. 块；
9. 强调。

标题
标题使用#表示，从#到######一共六级，井号月多标题越小，#从一行顶格开始，和标题名字中间用空格分开，例如：

# 这是一号标题
## 这是二号表标题
### 三号
###### 六号
1
2
3
4
显示效果如下：

这是一号标题
这是二号表标题
三号
六号
段落
段落之间通过两个空格+回车 区分，如果一行的结尾直接回车跟下一段，这两段显示的时候其实会显示成同一段。

列表
列表可分为有序列表和无序列表，由于列表与一般的列表相同，通过1.列表1、2. 列表2...这样的方式，无序列表通过星号*、加号+和减号-表示，显示效果都一样，例如：

* item1
+ itme2
- item3
1
2
3
会显示成：

item1
itme2
item3
图片
图片的显示方法感叹号+中括号+括号例如我的[外链图片转存失败,源站可能有防盗链机制,建议将图片保存下来直接上传(img-BjzumNy1-1587285341226)(https://imgconvert机制,建来csdn传(i.cn/aHg0cHMALy91cGxvYWQtaW8-1hZ2VzLmppYW5zaHUuavdXBsb8FkX2ltYWdlcy7yOTU4Njg2LWUyYTRhY2YyNTlmYmNmYTkucG1n?x-oss-process=image/format,png3)]()]]]]显示成下面这样：


链接
链接和图片类似，只要把图片前面的感叹号去掉就行。例如[LLVM,一堆积木的故事](https://www.jianshu.com/p/9ad4abbffac1)会显示成这样：LLVM,一堆积木的故事

表格
表格语法如下：

|表头1|表头2|表头3|
|:-:|:-:|:-:|
|one|two|three|
|four|five|sixsixsix|
1
2
3
4
显示如下

表头1	表头2	表头3
one	two	three
four	five	sixsixsix
引用
应用使用>表示，可以套娃引用，例如：

> 我引用了别人的一段话
>> 我引用了别人引用别人的一段话的一段话
>>> 我引用了别人引用别人引用别人的一段话的一段话的一段话

1
2
3
4
显示效果如下：

我引用了别人的一段话

我引用了别人引用别人的一段话的一段话

我引用了别人引用别人引用别人的一段话的一段话的一段话

块
块，更多的是用在显示代码，它可以保留代码的原是结构，当然，其实任何文本都可以放进去，它使得里面的文本不会被Mardown渲染成特殊显示效果，例如

# Infact I don't need to import anything, just an example
import torch
print('This is how code should be shown')
1
2
3
使用的方法是使用三个连续反引号（`，键盘左上方esc键下方，不是回车键旁边）将待码快包起来，反引号单独一行，顶格。行内的块用单个反引号

强调
斜体：使用两个星号包裹，例如*斜体内容*显示成斜体内容；
粗体：使用两个星号包裹，例如**粗体内容**显示成粗体内容；
斜体+粗体：使用三个星号包裹，例如***斜体+粗体内容***显示成***斜体+粗体内容***。
星号也可以用下划线代码，效果是一样的。

更多
更多更详细的语法请移步https://daringfireball.net/projects/markdown/syntax
————————————————
版权声明：本文为CSDN博主「SunnyZhou-1024」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/ZM_Yang/article/details/105617607
