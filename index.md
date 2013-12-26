---
layout: default
title: XP订票助手
---
{% include JB/setup %}

## 公告列表

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 软件简介

`XP订票助手`是一个基于<a href="http://www.12306.cn/" target="_blank" title="中国铁路客户服务中心网站">中国铁路客户服务中心网站</a>的火车票预订客户端软件，为了解决网上订票难而设计开发。

### 运行环境

Win8,Win7,Vista,WinXp,Win2000,Win2003

【注意: WinXp及以下系统需要<a href="https://www.microsoft.com/zh-cn/download/details.aspx?id=1639" target="_blank">.NET Framework</a>，如果您的系统中出现“初始化失败”的字样，请<a href="http://download.microsoft.com/download/c/6/e/c6e88215-0178-4c6c-b5f3-158ff77b1f38/NetFx20SP2_x86.exe" target="_blank">点击下载.NET Framework 2.0</a>！】

### 软件截图

<img src="image/index_1.jpg" />

## 软件特色

- 绿色软件，无需安装。
- 无需下载12306网站证书。
- 自动查询、自动提交。
