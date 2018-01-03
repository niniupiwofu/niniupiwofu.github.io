---
layout: article
title:  "修改文章底部个人信息的链接"
date:   2018-01-02 21:43:25 +0800
categories: posts rwd

image:
  feature: weibo.jpg
  teaser: weibo.jpg
 
---

### 文章底部个人信息链接的修改

效果如下图：

<img src="https://niniupiwofu.github.io/images/o.jpg" alt="01">


我以我增加的 **github** 及 **weibo** 个人主页为例


#### 第一步：找到 ```_sass```档 中的 ```_button.scss``` 文件 及 ```_variables.scss```文件，并打开；

#### 第二步：找到 ```_variables.scss```文件中的```Color variables```一栏，定义 **github** 及 **weibo** 两个颜色；如图：

<img src="https://niniupiwofu.github.io/images/t.jpg" alt="02">

#### 第三步：找到 ```_button.scss```文件中的 ```.btn-social```属性增加 ```(github, $github-color)``` 及 ```(weibo, $weibo-color)``` 两个元素；如图：

<img src="https://niniupiwofu.github.io/images/t.jpg" alt="03">

#### 第四步：打开 ```_includes```档 中的 ```share-this.html``` 文件，将名称和链接换成 **github** 和 **weibo** 的，并在后面加 ```/{ site.owner.github }```(此处是两个{ {  } } ), 这样它就会自动跳转到你的个人主页。具体操作如下图：

<img src="https://niniupiwofu.github.io/images/f.jpg" alt="04">

- **owner** 指的是```_config.yml```档的 **owner**栏。
- 微博需要先登录之后才能跳转个人主页。

