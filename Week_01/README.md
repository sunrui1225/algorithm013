学习笔记



在本周的作业里边简单的题我都已经完成，作业只提交了两道题。

我的心得如下：

1，优化思想：空间换时间。如例题 “接雨水”。

​							以栈为额外空间的数据结构，保存题目中的边界。如果符合计算，则弹出栈顶元素。

​							如果不符合，则入栈（又加入了一个边界）。

2，查找重复项。这个思路是解决递归问题的思路。如题目爬楼梯。

​							总的爬楼梯数 = 倒数第二梯（迈两步） + 倒数第一梯（迈一步）。

3，双指针法。对于求数组中几个数的和，求最大盛水面积，一般都是运用双指针发法。

​						如“两数之和”，“接雨水”。