---
layout: article
title: "高德地图POI"
categories: infovis

image: 
  teaser: infovis_final_work.jpg
  feature: infovis_final_work.jpg
---

## 摘要
城市地区的地图兴趣点（point of interest, POI）主要包括城市内具有标志性作用的实地建筑物，并描述这些实体建筑物的空间和属性信息。  
此次利用高德地图Web服务的[搜索API](http://lbs.amap.com/api/webservice/guide/api/search/)和数据可视化可视化软件tableau来探索以下关键词的POI：`动漫基地` `动漫城` `动漫电玩` `动漫餐饮` 

<hr style="border-top:3px solid #3f87a6;margin: 50px 0px 50px 0px;">

### 看图说话吧！
<div class='tableauPlaceholder' id='viz1516699441196' style='position: relative'><noscript><a href='#'><img alt='地图 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;_9&#47;_9715&#47;sheet8&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='_9715&#47;sheet8' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;_9&#47;_9715&#47;sheet8&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    var divElement = document.getElementById('viz1516699441196');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1016px';vizElement.style.height='991px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

从地图上可以看出大多POI都处在东部，特别是人口密集、流量大的省会城市或城市群也就不奇怪了。动漫城城最多，且各省均有分布。使用关键词筛选器，将动漫城取消勾选可以看到其他关键词的POI分布较动漫城就显得少且松散得多。

<div class='tableauPlaceholder' id='viz1516699158923' style='position: relative'><noscript><a href='#'><img alt='各地区分布 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;_1&#47;_18078&#47;sheet9&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='_18078&#47;sheet9' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;_1&#47;_18078&#47;sheet9&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    var divElement = document.getElementById('viz1516699158923');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1016px';vizElement.style.height='991px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

动漫城看起来比较普遍，我们来看看其他几个关键词在各个地区的分布情况。
东部地区依旧最多，其中名列前茅的是江苏省、上海市、安徽省和广东省。上海的人口和土地面积虽然不比广东和四川，但是POI数量却能与它们并驱争先（即使加上电玩城上海依旧排第二，仅次广东高于北京）。上海土地小人口多，人流量大且开放程度高为这座城市带来了多元的文化。

<div class='tableauPlaceholder' id='viz1516700754102' style='position: relative'><noscript><a href='#'><img alt='市场 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;_1&#47;_18810&#47;sheet10&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='_18810&#47;sheet10' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;_1&#47;_18810&#47;sheet10&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    var divElement = document.getElementById('viz1516700754102');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1016px';vizElement.style.height='991px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
我动漫产业的处于高速的发展期，二次元受众的比利也不断增高，即将成为主流的消费群体，从下图也可以看出中国的动漫产业的潜在消费群体数量巨大。


<hr style="border-top:3px solid #3f87a6;margin: 50px 0px 50px 0px;">


### 数据来源及数据处理

+ 数据来源

POI数据来自高德地图搜索服务API。数据可视化使用全国范围内截至2017年12月28号的数据，共**21386**条，每条POI数据包括**经度**、**纬度**、**名称**、**地址**、**类型**、**行政区**、**行政编码**和**联系电话**共**8**个属性。<br/>
按照类型统计，POI数据共归为**19**大类，如交通设施服务、住宿服务、体育休闲服务、生活服务、餐饮服务、科教文化服务等。每一大类下又包括多级小类。以餐饮服务类为例，该一级类别下又包括中餐厅、咖啡厅和快餐厅等二级类别.
另外还从国家数据网提取了地区分类（东中西）数据。
<br/>  

+ 数据处理

原始POI数据分类较多，且每一大类下包括多级小类，类型之间存在重复交叉现象(详见[高德地图POI分类编码](http://lbs.amap.com/api/webservice/download))，如宿舍既存在于商务住宅的住宅区中，同时又存在在科教文化服务的学校中，因此需要对原始数据重分类。经过筛选之后，我得到了**8282**条数据。

> - 作者的话：

    做动漫产业的数据可视化是因为我想证明我们死宅也并不如人们口中所传的对这个世界毫无贡献，作为中国快速发展的新兴的产业，动漫产业的主要消费对象就是我们死宅，而也可以证明死宅的消费市场非常巨大。所以我们死宅也是有对国家的GDP做出贡献的，请不要再说死宅每天只会吃喝睡觉打游戏看动漫，我们在某种意义上也是推动的国家的发展的。


<hr style="border-top:3px solid #3f87a6;margin: 50px 0px 50px 0px;">






<div class="tiles">
{% for post in site.categories.infovis %}
{% include post-grid.html %}
{% endfor %}
</div>
