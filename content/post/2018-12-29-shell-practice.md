---
title: shell 命令实战合集
category: 编程
date: 2018-12-29T09:21:11.000Z
tags: Shell
published: true
---

- linux 下使用命令排除当前行及下一行的内容
```shell
sed '/关键字/,+1d' file >file2
```

