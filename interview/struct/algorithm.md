# 大顶堆和小顶堆

比如求10亿个数中的最大的前10个数，时时构建只有10个元素的小顶堆，如果比堆顶小，则不处理；如果比堆顶大，则替换堆顶，然后依次下沉到适当的位置。

比如求10亿个数中的最小的前10个数，时时构建只有10个元素的大顶堆，如果比堆顶大，则不处理；如果比堆顶小，则替换堆顶，然后依次下沉到适当的位置。

# 堆排序的原理

- [图解排序算法(三)之堆排序](https://www.cnblogs.com/chengxiao/p/6129630.html)

# 求TOPk的问题

1. 使用小顶堆求Topk
2. 使用快速查找法找到第K大的元素，剩下的一边就是topK
3. 全排序

# KMP算法

一种字符串查找算法

参考链接：

- [从头到尾彻底理解KMP](https://blog.csdn.net/v_july_v/article/details/7041827)
- [阮一峰讲解](http://www.ruanyifeng.com/blog/2013/05/Knuth%E2%80%93Morris%E2%80%93Pratt_algorithm.html)

# LRU实现

最小访问的算法实现

- [LRU缓存实现(Java)](https://www.cnblogs.com/lzrabbit/p/3734850.html)