# 图片爬虫

## 目录

* core：内核代码
  * index.html	//搜索参数填写,action => getHtml.php

  * getHtml.php  //url生成，下载页面，代理，de反爬虫

  * getWallpaper.php  //用simple_html_dom分析获取图片

  * commander.php  //控制器
* lib：第三方库
  * php-phantomjs
  * phantomjs
  * simple_html_dom.php
* download：下载的资源
* reference：参考资料
* remdme.md
* composer.json
* composer.lock

## 思路

* 用phantomjs提取url
* 用simple_html_dom分析页面
* ​

## log

2018.3.26	架构分析