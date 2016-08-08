---
layout: post
title:  Makdown Tips
date:   2016-07-27 13:50:39
categories: tools
---

# 善其工，利其器

(Sublime Text 3 Markdown 插件推荐）

*   OmniMarkupPreviewer[^1]
    -   ctrl+alt+o 打开默认浏览器预览
*   MarkdownEditing
    -   mdl+tab 插入链接
    -   mdi+tab 插入图片
    -   mdc+tab 插入code
    -   mdh{1-6}+tab 插入标题
    -   alt+shift+6 插入脚注


# Markdown 语法  [^2]#

## 标题 ##
```md
# 一级标题 #
## 二级标题 ##
### 三级标题 ###
...
###### 六级标题 ######
```
## 列表 ##

无序列表使用星号、加号或是减号作为列表标记；有序列表则使用数字接着一个英文句点。

## 链接 ##
两种形式的链接，不管是哪一种，链接文字都是用 [方括号] 来标记。

*   行内式

语法部分 [参考文献](http://wowubuntu.com/markdown/ "语法说明")

*   参考式

语法部分 [参考文献] [1]

[1]: http://wowubuntu.com/markdown/

## code ##
小行代码使用反引号标记 `` ` ``

代码块 `` ``` ``

```java
System.out.println("Helloword");
```

# Table #

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```

![_config.yml](/static/img/loadingAnimation.gif)

![logo]({{ site.baseurl }}/static/img/logo.png)

[^1]: http://blog.leanote.com/post/54bfa17b8404f03097000000
[^2]: http://wowubuntu.com/markdown/