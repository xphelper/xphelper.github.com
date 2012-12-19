---
layout: default
title: XP订票助手
---
{% include JB/setup %}

## 软件简介

`XP订票助手`是一个基于<a href="http://www.12306.cn/" target="_blank" title="中国铁路客户服务中心网站">中国铁路客户服务中心网站</a>的火车票预订客户端软件，为了解决网上订票难而设计开发。目前还处于外测阶段。
<img src="image/index_1.jpg" />

## 软件特色

- 绿色软件，无需安装。
- 无需下载12306网站证书。
- 智能识别验证码，正确率90%以上。
- 一键式全自动无人看管。

## 公告列表

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>