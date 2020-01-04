redis 源码阅读，基于`redis 5.0.7`。

在源码之上增加注释，后续会为其中一些值得拎出来说的点单独写文章。

源码目录为`/redis-5.0.7/src`。

阅读完的代码文件，我会给文件名添加前缀`yoko_`，比如`adlist.c -> yoko_adlist.c`

底层基础数据结构：

| 文件名 | 进度 |
| - | - |
| dict.c[.h] | 95% |
| adlist.c[.h] | 100% |
| sds.c[.h] | working |
