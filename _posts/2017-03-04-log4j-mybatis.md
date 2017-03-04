---
layout: post
title: "log4j精确调试mybatis"
date:   2017-03-04 23:06:05
categories: log4j
tags: log4j配置 mybatis
author: Hcx
---

* content
{:toc}

## log4j.properties文件

* Global logging configuration

 > log4j.rootLogger=ERROR, stdout

*  MyBatis logging configuration...

 > log4j.logger.com.web.mapper.TestMapper=TRACE
   log4j.logger.com.web.mapper=DEBUG

![](http://chunxinhou.github.io/images/log4j-mybatis.png)

* Console output...

 > log4j.appender.stdout=org.apache.log4j.ConsoleAppender
    log4j.appender.stdout.layout=org.apache.log4j.PatternLayout
 log4j.appender.stdout.layout.ConversionPattern=%5p [%t] - %m%n
