---
layout: post
title: "mybatis连接mysql的时候报时区错误"
date:   2017-03-03 22:06:05
categories: mysql
tags: mysql bug
author: Hcx
---

* content
{:toc}

## 异常表现：
> ERROR: The server time zone value '�й���׼ʱ��' is unrecognized or represents more than one time zone. You must configure either the server or JDBC driver (via the serverTimezone configuration property) to use a more specifc time zone value if you want to utilize time zone support.

## 查看时区
>show variables like '%time_zone%';

![]:(http://chunxinhou.github.io/images/mysqlbug.jpg)
