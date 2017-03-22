---
title: 单步调式Nginx
date: 2017-03-22 12:47:00
tags:
---

在Nginx的配置文件中加入以下,就可以方便`gdb`调试了.
```
daemon off;
master_process off;
```

`configure`时带上`--with-debug`, 用来看log

[Nginx文档链接](http://nginx.org/en/docs/ngx_core_module.html)