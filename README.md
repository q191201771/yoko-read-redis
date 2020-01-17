2020年，给自己加个任务，把 redis 代码完整读一遍。

在源码之上增加注释，后续会为其中一些值得拎出来说的点单独写文章。

源码目录为`/redis-5.0.7/src`。

基于`redis 5.0.7`。

| 文件名 | 进度 | 简述 |
| - | - | - |
| dict.c[.h] | 95% | 底层基础数据结构，字典，基于哈希表实现 |
| adlist.c[.h] | 100% | 底层基础数据结构，双向链表 |
| sds.c[.h] | 80% | xxx |
| sdsalloc.h | 80% | xxx |
| zmalloc.c[.h] | 80% | xxx |
| intset.c[.h] | 95% | xxx |
| endianconv.c[.h] | 95% | 大小端相关 |

相关文章：

- [redis源码阅读之面向哈希表优化](https://pengrl.com/p/20010/)
