# Redis Internals

* [English](https://github.com/zpoint/Redis-Internals/blob/5.0/README.md)

这个仓库是我分析 [redis](https://github.com/antirez/redis) 源码时做的记录

    # 基于版本 5.0.5
    cd redis
    git fetch origin 5.0:5.0
    git reset --hard 388efbf8b661ce2e5db447e994bf3c3caf6403c6

# 目录

* [为什么创建这个仓库](#为什么创建这个仓库)
* [学习资料](#学习资料)

# 为什么创建这个仓库

* 出于学习目的
* 在 [学习资料](#学习资料) 中有非常棒的中文书籍可以参考, 但是没有类似的英文资料
* [Redis 设计与实现](http://redisbook.com/) 一书s是基于 redis 3.0 版本的(我读的时候是旧版 基于2.x版本), 即使是 redis 3.0 到当前版本许多实现细节也发生了变化

# 学习资料

* [Redis 设计与实现](http://redisbook.com/)
* [Redis 5.0 RELEASENOTES](https://raw.githubusercontent.com/antirez/redis/5.0/00-RELEASENOTES)