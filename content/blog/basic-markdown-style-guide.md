---
external: false
title: "“基础MD风格指南”"
description: "You can author content using the familiar markdown syntax you already know. All basic markdown syntax is supported."
date: 2022-11-02
---

Markdown由[Markdoc]提供支持(https://markdoc.dev/). 这是一篇演示所有基本markdown语法的示例文章。您可以使用熟悉的markdown语法编写内容。 

## 内联格式

粗体: **此文本为粗体**.

斜体: _此文本为斜体_.

删除: 您可以 ~~删除~~ 文本.

内联代码：您可以添加这样的内联代码`const hello = "world"`.

## 标题

以下“HTML“”<h2>“-”<h6>”元素表示五个级别的节标题“<h1>”也可用，但不建议使用，因为文章标题已经是“＜h1＞”元素，因此在一个页面中有多个“＜h1>”元素不是一个好的做法。

## H2: 标题二

### H3: 标题三

#### H4: 标题四

##### H5: 标题五

###### H6: 标题六

## 段落

一段单独的文本。


段落也可以是多行的，当它们组成一行以上的单词时，即它们换行到下一行。哇！我真的很聪明，能写出两行毫无意义的文字。



## 块引号

> 这是一个大引号。而且时间也很长。足够长，可以换行到下一行。它肯定会包起来的。

> 您可以在块引号中使用其他Markdown语法，如`inline code` .

## 表格

| 斜体   | 粗体     | 代码   |
| --------- | -------- | ------ |
| _斜体_ | **粗体** | `代码` |

## 列表 类型

### 已排序 列表

1. 第一项
2. 第二项
3. 第三项

### 未排序 列表

- 列表项目
- 另一项
- 还有一项

### 嵌套 列表

- 水果
 - 苹果
 - 橙色
 - 香蕉
- 乳制品
 - 牛奶
 - 奶酪

## 代码 块

语法高亮显示使用[Prism.js]完成(https://github.com/PrismJS/prism). 您可以从[大量可用的棱镜主题]中定制您想要的主题(https://github.com/PrismJS/prism-themes).

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```

## Images

![Blogster](/images/blogster.png)
