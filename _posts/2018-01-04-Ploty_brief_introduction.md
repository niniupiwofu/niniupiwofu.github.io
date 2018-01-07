---
layout: article
title:  "python plotly简介"

categories: posts infovisnote

image:
  feature: plotly_logo.jpg
  teaser: plotly_logo.jpg
 
---

# 简单介绍python逆天的plotly功能及其安装方法。

Plotly，一个用于做分析和可视化的在线平台，曾被网友称为“有史以来最牛逼”可视化神器（具体无从考据，只是在搜索资料时看到的），为何有如此称号？因为它功能强大，功能强大，功能强大！重要的事情说三遍！

其功能强大到不仅与多个主流绘图软件的对接，而且还可以像Excel那样实现交互式制图，而且图表种类齐全，并可以实现在线分享以及开源，等等；这种功能强大到还没有一个人能够完全掌握其全部应用，甚至国内对它的介绍使用也仅仅只是其中一部分。

## （一）关于**Plotly**的功能
关于Plotly的功能介绍，有的从图表类型上：基本图表：20种；统计和海运方式图：12种；科学图表：21种；财务图表：2种；地图：8种；3D图表：19种；拟合工具：3种；流动图表：4种。

有的从交互性上：可以与 **R、python、matlab** 等软件对接，并且是开源免费的，对于**Python，Plotly与Python**中**matplotlib、numpy、pandas**等库可以无缝地集成，可以做出很多非常丰富，互动的图表，并且文档非常健全，创建图形相对简单，另外申请了API密钥后，可以在线一键将统计图形同步到云端。

有的从制图的美观上：基于现代的配色组合、图表形式，比matpltloa、R语言的图表，更加现代、绚丽。

即便如此，尚不能完全概括其功能，比如在图表类型上，除以上所说，由于其开源性，plotly上还有很多网友上传的自制图表，在plotly主页（Visualize Data, Together ）点击try free edition，在不登录的情况下（出来的log in 对话框点X），就会看到很多网友分享的图表，并且可以看到其代码。

## （二）关于Plotly的python使用

在Plotly网站，点击Python软件类型选择件就可以进入专门使用python的主页 [Plotly](https://plot.ly/python/)：
![plotly](https://pic4.zhimg.com/50/v2-c71ee6f3a47e6db43f99164acfbc6783_hd.jpg)

左侧一列是导航，包含如何开始使用，使用说明，离线使用以及于其他库结合使用，还有例子，正文中下边就是各种图形，需要用哪种图形就可以点击进去寻找代码。特别说明的是：Plotly需要注册之后，并将注册名与密码放入代码里才能使用。

在Python使用plotly，首先要 ``安装plotly库```，在Plotly——getting start里有说明：

> - 安装方法:
    
	pip install plotly 或者 sudo pip install plotly

> - 需要升级的话，可以输入：
    
	pip install plotly –upgrade
	
	注册，在python交互环境下运行以下初始化命令，生成认证的安全文件 .plotly/.credentials。
	
	py = plotly.plotly("Username", "API-Key")