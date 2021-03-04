# Coding Girls Day

这里写一些关于Coding Grils Day和本仓库的介绍 -- 文洋

## [点击这里进入案例](https://hackerstart.github.io/girls-coding-day/)

## 搭建网站

### 第一步：注册GitHub

请点击这里[注册GitHub](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home), 注册成功之后，登录GitHub。

如果你已经有GitHub账户，请跳过这一步！

### 第二步：Fork本仓库

登录到GitHub之后，点击这里进入仓库[girls-coding-day](https://github.com/HackerStart/girls-coding-day)，点击右上角的Fork按钮。

![fork](https://tva1.sinaimg.cn/large/008eGmZEly1go88cvsfyrj326m0m6afi.jpg)

等待Fork成功之后，此仓库将进入自己的账户下面。

### 第三步：搭建GitHub Pages

首先进入此仓库Settings页面：

![Setting](https://tva1.sinaimg.cn/large/008eGmZEly1go88g55xv5j324o0gon15.jpg)

找到GitHub Pages设置区域, 点击Source下面的下拉框，选择`gh-pages`分支之后，点击Save按钮。

![Github Pages](https://tva1.sinaimg.cn/large/008eGmZEly1go88kkzv47j31j20n4djh.jpg)

访问下面的URL，你的GitHub Page就发布成啦！

![github-pages-url](https://tva1.sinaimg.cn/large/008eGmZEly1go891w7spjj31hu0tedkv.jpg)

可能由于GitHub Pages有延迟和缓存的问题，你可以等一会儿访问，或者在这个URL地址后面加上`index.html`就可以预览啦！

## 发表你的博客

### 第一步：修改网站的主题和标题

你可以在`_config.yml`文件中修改网站主题和副标题等一些信息。

```yml
# Site settings
title: # 网站主题
subTitle: # 网站标题
description: # 网站的描述
keywords: # 网站的关键词
author: # 网站作者
```

找到该文件，点击进入，文件的右上角有一个铅笔字样的编辑按钮，点击编辑按钮可以进行编辑。编辑完成后，点击下方的`Commit Change`按钮保存文件。文件保存之后，等几分钟刷新你网站的页面，你就可以看到效果啦！

### 第二步：创建博客

点击进入`_posts`文件夹下面，点击右上角的`Add File`按钮，选择`Create new file`之后进入编辑页面。

![create new file](https://tva1.sinaimg.cn/large/008eGmZEly1go89fohkb1j31yo0b076r.jpg)

在编辑页面输入文件名称，名称符合如下格式：
* 文件名必须以日期开头，如`2020-10-11`
* 文件名必须使用英文命名，多个单词之间用中划线`-`连接
* 日期与英文之间用`-`中划线连接
* 文件名必须以`.markdown`结尾

在`Edit new file`文件空白区域输入`Markdown`语法, 书写自己的故事，当然你可以通过`Preview`按钮边书写故事边预览效果！

![edit-new-file](https://tva1.sinaimg.cn/large/008eGmZEly1go89mp6brkj31om0g0wg6.jpg)

### 第三步：给博客添加属性

在你创建的博客的最上端，添加如下的内容，为你的博客添加头图，名称，作者等属性。

```yml
---
title:  "Girls Coding Day" 
subtitle: "The Fly!"
author: "Wferr"
avatar: "img/authors/cabbage.png"
image: "img/girl.jpg"
date:   2020-03-08 12:12:12
---
```

将你准备好的图片放到`img`文件夹下面，更新`image`为`img/图片名称`。

### 第四步：发表自己的博客

点击最下面的`Commit new file`按钮，提交该文件，进入网站首页，找到自己添加的图片，点击图片查看自己的博客。

到这里，相信你已经有了自己的网站，同时发表了自己的博客哦！
