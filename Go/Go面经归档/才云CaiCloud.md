一面
先问项目，问项目细节，从项目中学到了什么
再问算法，TopK问题

二面
先问项目，问的比较深入，要求对使用的工具的原理有了解(问了ci/cd的原理)，而且要求对项目的实现由比较深入的了解
再问算法：
1.有一个数组中有一个超过半数的数，找出来
答：第一种：排序，然后找到中位数。第二种：每次取两个数出来，如果不一样，就在数组中剔除这两个数，最后数组中剩下的就是要求得数。
2.在数组中找到和为k的两个数，要求乘积最小。
答：排序，然后指针对撞，第一个取到的和就是乘积最小的
然后问基础：
1.Go语言基础，协程之间的通讯（channel、全局变量），协程的优雅退出（waitgroup，channel，context），用协程实现的快排
2.Docker的基本操作，dockerfile的书写（从外面复制文件到镜像里面，ADD）
最后问了一些其他的问题
1.英语能力如何
2.对开源项目的贡献

结果：顺利offer