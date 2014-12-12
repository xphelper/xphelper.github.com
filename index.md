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

- 绿色软件，无需安装，无需下载12306网站证书；
- 可记录登录的用户名和密码，打开登录界面后自动填写；
- 在抢票过程中，自动保持登录状态；
- 出发城市目的城市可根据汉字、拼音首字母自动提示；
- 自动刷新查询，可以自由配置查询时间间隔；
- 自动提交订单，直到提交成功，提交成功后，有提示音，显示订单信息；
- 可自由选择任意车次任意席别组合；
- 支持轮询日期，可设置多个日期，轮番刷新查询；
- 支持邮件提醒，订单提交成功后，向指定邮箱发送提醒邮件；
- 支持云打码，提交过程中，可不输入验证码；
- 支持定时抢票，设置好出票时间，时间一到，立即抢票；

## 独创功能

【多CDN模式】：运行一个软件，同时连接多台不同服务器，有效过滤CDN缓存带来的过期数据，率先获取最新车票信息，快人一步提交订单，抢票成功率明显提高。


## 友情链接

<a href='http://www.jisuxz.com/'>极速下载</a> | <a href='http://www.huacolor.com/'>华彩软件站</a>