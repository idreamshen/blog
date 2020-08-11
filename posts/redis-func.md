---
title: "Redis 几个常用的简单命令"
date: 2015-08-11T15:27:19+08:00
draft: false
---

### redis-cli
连接数据库
例子：`redis-cli` 连接到本地
例子：`redis-cli -h 192.168.1.27` 连接到远程

### type
查看某个 key 的类型
例子：`type key`，返回的结果可能有 `string`，`set`，`list` 等

### keys
查看所有的 key
例子：`keys *`

### smembers
查看某个 sets 类型的所有成员
例子：`smembers key`

### hgetall
查看某个 hash 类型的所有成员
例子：`hgetall key`

