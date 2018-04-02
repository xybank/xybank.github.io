# xybank.github.io

## 融易通兴业团队

### 博客编写格式：

#### 一、文件名

文件命名必须由 `大小写字母` 或 `_` 构成，否则 Linux 上可能会出现乱码。

#### 二、内容头部

博客 md 头部必须包含以下几项：

title // 文章标题  
date // 创建时间  
tags // 文章属性标签，可以填多个（控制在3个以内），用英文','隔开，尽量填辨识性高的标签  
categories 作者姓名  
description // 显示在首页的文章描述部分，允许不写此标签，但是如果不写此标签，文章第一段必须用 `<!--more-->` 结尾，表示第一段为描述内容  

示例：

```
---
title: 基于hexo搭建GitHub静态博客
date: 2018-03-23 19:05:00
tags: [hexo, GitHub]
categories: 蔡向炜
description: 搭建博客参考教程
---
```

#### 三、内容正文

文章正文部分请按照 MarkDown 格式认真编写，语法不清楚的可以参考：[CSND模板下载](https://xybank.github.io/download/MarkDown.rar)

#### 四、图片

图片是比较常用的内容格式之一，如果有图片，请在 `source/img` 下新建文件夹放置，为避免与他人冲突，请新建属于自己的文件夹。如：`img/hexo` ，在 md 中格式为： `![Folder](/img/hexo/folder.jpg)` 。  

#### 五、文件下载

如果有提供文件下载，统一放在根目录下的 `download` 文件夹中。不建议有文件下载，如果有源码，可以上传到自己的 GitHub 上，并给出对应的链接。如： `download/MarkDown.rar` 文件，在 md 中格式为：`[CSND模板下载](/download/MarkDown.rar)`

#### 六、团队博客效果预览

此博客（`xybank.github.io`）的主题是用的 [Maupassant](https://github.com/tufu9441/maupassant-hexo) ，想预览效果可以按照文档，安装该主题。当前博客的配置文件可以下载参考：[配置文件下载](https://xybank.github.io/download/blog_onfig.rar)

