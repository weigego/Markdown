

# Markdown syntax notes

(updated last: 2022/01/10)

source:

1. https://zhuanlan.zhihu.com/p/86516807
2. https://blog.csdn.net/ZM_Yang/article/details/105617607
3. https://support.typora.io/Markdown-Reference/
4. https://www.markdownguide.org/cheat-sheet/

> Good things take time.

Topics to cover:

1. 标题；
2. 段落；
3. 列表；
4. 图片；
5. 链接；
6. 表格；
7. 引用；
8. 块；
9. 强调

## headline

` # 一级

` ## 二级

` ### 三级

` #### 四级

` ##### 五级

` ###### 六级

` ####### 七级

最多到六级。



## Bold,  Italic, bold & italic

加粗：选中文字，按ctrl+b，或者使用 **加粗**。

斜体：选中文字，按ctrl+i，或者使用*斜体*

加粗斜体：使用***加粗斜体***

## List

### Unordered List

使用`* `

* unordered list1
* unordered list2

或者使用 `- `

- 无序列表1
- 无序列表2

### Order List

1. order list1
2. order list2

## CodeBlock 块

`单行字符`

```
多行代码
多行代码
```

## Horizontal cutting line 水平分割线

使用 `---`表示分割线，如下：

---

## Reference 引用

use `>`

> Lu Xun said, time is haimian, suck suck always OK



## Form

使用竖线分割各个单元格、冒号决定单元格的对齐方向，如下：

```html
| 学号 | 姓名 |
| :--: | :--: | 
| 110  | wei  |
| 111  |  ge  |
```
效果如下：

| 学号 | 姓名 |
| :--: | :--: |
| 110  | wei  |
| 111  |  ge  |



## Hyperlink

use `[description of the link](link)`

[description of the link](link)



## Image

use exclamation point `![description to the pic](link to the pic)`

example1: load image from local file

`<img src="G:\OneDrive - GTIIT\图片\HKUST壁纸\HKUST Zoom_BG7.jpg" alt="description to the pic" style="zoom:10%;" />`

and this leads to the following:

<img src="G:\OneDrive - GTIIT\图片\HKUST壁纸\HKUST Zoom_BG7.jpg" alt="description to the pic" style="zoom:10%;" />

example2: load image from internet

`![Guangdong Technion.png](https://upload.wikimedia.org/wikipedia/en/thumb/e/ed/Guangdong_Technion.png/220px-Guangdong_Technion.png)`

and this leads to the following:

![Guangdong Technion.png](https://upload.wikimedia.org/wikipedia/en/thumb/e/ed/Guangdong_Technion.png/220px-Guangdong_Technion.png)

