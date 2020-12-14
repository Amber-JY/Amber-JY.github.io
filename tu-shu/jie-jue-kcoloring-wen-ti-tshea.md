---
description: 使用禁忌搜索（TabuSearch）算法、混合进化算法（HybridsEvolution Algorithm）解决K色图涂色问题。
---

# 解决K-coloring问题——TS、HEA

## 引言

对于优化问题有以下分类:

![&#x4F18;&#x5316;&#x95EE;&#x9898;&#x5206;&#x7C7B;](../.gitbook/assets/20170112160649586.jpg)

禁忌搜索（TS）由局部搜索发展而来，局部搜索由爬山法发展而来。在了解禁忌搜索之前先熟悉这两种算法。

## 一. 什么是禁忌搜索算法（TS）

1. **爬山算法** 爬山算法从当前的节点开始，和周围的邻居节点的值进行比较。 如果当前节点是最大的，那么返回当前节点，作为最大值 \(既山峰最高点\)；反之就用最高的邻居节点来，替换当前节点，从而实现向山峰的高处攀爬的目的。如此循环直到达到最高点。 因为不是全面搜索，所以结果可能不是最佳。兔子可能只找到了泰山，就不再进行搜索了。
2. **局部搜索算法** 局部搜索算法是从爬山法改进而来的。局部搜索算法的基本思想：在搜索过程中，始终选择当前点的邻居中与离目标最近者的方向搜索。同样，局部搜索得到的解不一定是最优解。
3. **禁忌搜索算法** 
4. \*\*\*\*







## 参考：

华中科技大学SmartLab实验室 吕志鹏教授PPT 

{% file src="../.gitbook/assets/ch3\_hybrid-evolutionary-algorithm-for-graph-coloring\_2018.09\_new.pdf" caption="TS、HEA、HEAD算法PPT" %}

[https://blog.csdn.net/tyhj\_sf/article/details/54235550](https://blog.csdn.net/tyhj_sf/article/details/54235550)

[https://www.jianshu.com/p/00aba9b8c017](https://www.jianshu.com/p/00aba9b8c017)

[https://www.cnblogs.com/dengfaheng/p/9737556.html](https://www.cnblogs.com/dengfaheng/p/9737556.html)



