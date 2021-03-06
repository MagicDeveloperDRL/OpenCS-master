# 《LeetCode刷题宝典》题单答案

 该项目记录作者刷LeetCode的题单《剑指Offer(第2版)》的C++实现。

[TOC]

# 【数组】

## 【二分查找（2+2）】

[数组和字符串之二分查找的C++实现](./1-1-数组和字符串之二分查找、双指针、滑动窗口.md)

### （1）二分查找含重复元素的数字

### （2）二分查找旋转排序数组

## 【双指针（2+1）】

[数组和字符串之双指针的C++实现](./1-1-数组和字符串之二分查找、双指针、滑动窗口.md)

### （1）移动数组中的元素

### （2）查找排序数组中的2个数

## 【滑动窗口（1）】

[数组和字符串之滑动窗口的C++实现](./1-1-数组和字符串之二分查找、双指针、滑动窗口.md)

### （1）连续子序列

## 【二维矩阵（4）】

[数组和字符串之二维矩阵的C++实现](./1-2-数组和字符串之二维矩阵.md)

### （1）二维矩阵匹配字符数组

### （2）检查二维矩阵中有多少个元素符合要求

### （3）从升序二维数组中快速查找某个数

### （4）螺旋遍历二维矩阵

## 【位运算（5+5）】

[数组和字符串之位运算的C++实现](./1-4-数组和字符串之位运算.md)

### （1）二进制计数（汉明距离和汉明权重）

### （2）数组中元素出现的次数

#### A、一个数出现1次，其余数都出现3次

#### B、二个数出现1次，其余数都出现2次

### （3）四则运算

#### A、二进制加法

## 【数学规律（5）】

[数组和字符串之数学规律的C++实现](./1-5-数组和字符串之数学规律.md)

### 【实现简单的指数函数（快速幂）】

### 【N位数的规律】

​			LeetCode中有一类题专门考察数字的位数，请先掌握以下规律：假设有一个n位数，

| n位数 | 数字范围          | 数字数量     | 数位数量       |
| ----- | ----------------- | ------------ | -------------- |
| 1     | `[0,10)`          | 9            | 9*1=9          |
| 2     | `[10,100)`        | 90           | 90*2=180       |
| 3     | `[100,1000)`      | 900          | 900*3=2700     |
| ...   | ...               | ...          | ...            |
| n     | `[10^(n-1),10^n)` | `9*10^(n-1)` | `9*10^(n-1)*n` |

可见随着n的增加，n位数的个数指数级增长。

### 【确定有限状态自动机】

​	   确定有限状态自动机（Deterministic Finite Automation）简称DFA，是一个用于实现状态转移的计算模型。DFA一般用于字符串的题目中，用于解决「对于给定的输入字符串 S，判断其是否满足条件 P」的问题。在工程上，其常见的就是实现[正则表达式]的功能。

​	[剑指 Offer 20. 表示数值的字符串](https://leetcode-cn.com/problems/biao-shi-shu-zhi-de-zi-fu-chuan-lcof/)

# 【字符串专属】

[字符串专属的C++实现](./字符串.md)

### 【反转字符串】

### 【分割字符串】

### 【旋转字符串】

### 【字符串比较大小】

# 【栈（2）】

[栈和队列的C++实现](./2-1-栈和队列.md)

## 【设计最小栈】

## 【验证栈序列】

# 【队列（3）】

[栈和队列的C++实现](./2-1-栈和队列.md)

## 【用两个栈实现队列】

## 【双端队列】

## 【优先级队列】

# 【哈希表（6）】

[哈希表的C++实现](./3-1-哈希表.md)

## 【找出一个序列中某个特殊的数】

## 【找出两个序列中不一样的地方】

## 【哈希表+滑动窗口】

# 【链表（8）】

[链表的C++实现](./4-1-链表.md)

## 【删除链表】

## 【反转链表】

## 【链表相交】

## 【合并链表】

## 【复制链表】

## 【链表与二叉树】

# 【二叉树（10）】

[二叉树的C++实现](./5-1-二叉树.md)

## 【层序遍历】

## 【从数组中构建二叉树】

## 【自顶向下遍历树】

## 【自顶向下计算属性】

## 【自顶向下回溯路径】

## 【自底向上寻找祖先】

# 【二叉搜索树（3）】

[二叉搜索树的C++实现](./5-2-二叉搜索树.md)

## 【最近公共祖先】

## 【中序遍历】

## 【分治递归】

# 【递归回溯（2）】

[递归回溯的C++实现](./6-1-递归回溯.md)

剑指 Offer 64. 求1+2+…+n（中等难度）

剑指 Offer 38. 字符串的排列（中等难度）

# 【贪心算法（2）】

[贪心算法的C++实现](./7-1-贪心算法.md)

剑指 Offer 14- I. 剪绳子（中等难度）

剑指 Offer 14- II. 剪绳子 II（中等难度）

# 【动态规划（8）】

[动态规划的C++实现](./8-1-动态规划.md)

## 【爬楼梯问题】

## 【网格路径】

## 【序列问题】

## 【丑数问题】

## 【约瑟夫环】

## 【骰子问题】

剑指 Offer 60. n个骰子的点数

## 【股票问题】

## 【乘积数组】

