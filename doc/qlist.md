# qlist
---

## 核心的数据结构

![](./pics/boltdb-kernel.png)

## Q1: 插入 key 时，怎么决定写入那个 page？

set操作： 本质上对应的是 set->node->page->file的过程

get操作： 本质上对应的是 file->page->node->get的过程

## Q2：page 中的 overflow 使用