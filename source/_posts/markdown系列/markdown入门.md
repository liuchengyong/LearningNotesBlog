---
title: markdown入门
tags:
  - markdown
categories:
  - markdown
abbrlink: 40122
date: 2022-02-09 18:00:30
---

### 标题

要创建标题，请在标题文本前添加一至六个 # 符号。 您使用的 # 数量将决定标题的大小。
```
# 最大标题
## 第二大标题
###### 最小标题
```

### 样式文本
|样式|语法|示例|输出|
|:----:|:----:|:----:|:----:|
|粗体|** ** 或 __ __|`**这是粗体文本**`|**这是粗体文本**|
|斜体|* * 或 _ _|`*这是斜体文本*`|*这是斜体文本*|
|删除线|~~ ~~|`~~这是错误文本~~`|~~这是错误文本~~|
|粗体和嵌入的斜体|** ** 或 _ _|`**此文本_非常_重要**`|**此文本 _非常_ 重要**|
|全部粗体和斜体|*** *** 或 _ _|`***所有这些文本都很重要***`|***所有这些文本都很重要***|


### 引用文本
```
> Text that is a quote
``` 
> Text that is a quote

### 引用代码
```
git status
git add
git commit
```

### 链接
```
[百度一下](http://wwww.baidu.com)
<www.baidu.com>
```
[百度一下](http://wwww.baidu.com)
<www.baidu.com>

### 章节链接
```
[样式文本](#样式文本)
```
[样式文本](#样式文本)

### 相对链接
```
[01｜开篇｜浏览器工作原理与实践](../54063/)
```
[01｜开篇｜浏览器工作原理与实践](../54063/)

### 图像
```
![This is an image](../../images/header.jpg)
```
![This is an image](../../images/header.jpg)

### 列表

```
- George Washington
- John Adams
- Thomas Jefferson

1. James Madison
2. James Monroe
3. John Quincy Adams
```
通过在一行或多行文本前面添加 - 或 * 可创建无序列表。
- George Washington
- John Adams
- Thomas Jefferson

要对列表排序，请在每行前面添加一个编号。
1. James Madison
2. James Monroe
3. John Quincy Adams
   
### 嵌套列表
通过在一个列表项下面缩进一个或多个其他列表项，可创建嵌套列表。
```
1. James Madison
    - George Washington
        - John Adams
        - Thomas Jefferson
    - John Adams
2. James Monroe
3. John Quincy Adams
```
1. James Madison
    - George Washington
        - John Adams
        - Thomas Jefferson
    - John Adams
2. James Monroe
3. John Quincy Adams

### 任务列表
`-[ ]` 要将任务标记为已完成，请使用 `[x]`。
```
- [x] todo1
- [ ] todo2
- [ ] todo3
```
- [x] todo1
- [ ] todo2
- [ ] todo3

### 段落
通过在文本行之间留一个空白行，可创建新段落。

