# 练习二 线性表

## 第一部分 线性表
 
1. 实现线性表的顺序存储结构，并分析每个基本操作（算法）的时间复杂度。
2. 实现线性表的带表头结点的单链表存储结构，并分析每种基本操作（算法）的时间复杂度。 
3. 实现线性表的不带表头结点的单链表存储结构，并分析每种基本操作（算法）的时间复杂度。 
4. 实现线性表的游标存储结构，并分析每种基本操作（算法）的时间复杂度。
5. 利用线性表知识，设计并实现银行存款利率表。

> 要求:  
> 1. 选择适当的存储结构，并说明理由；  
> 2. 存款利率表存储在文件中；  
> 3. 能够对利率表进行建立、修改、查询等编辑管理；  
> 4. 并能根据存期，计算相应的利息。  

2. 利用线性表知识，设计并实现自己的通讯录管理。 

> 要求：  
> 1. 选择适当的存储结构，并说明理由；  
> 2. 通讯录以文件的方式存储；  
> 3. 能够对通讯录进行建立、修改、插入、删除、排序、查询等。  

## 第二部分 栈和队列

1. 假设以不带头结点的循环链表表示队列，并且只设一个指针指向队尾结点，但不设头指针。试设计相应的入队和出队的算法。 
2. 设顺序栈 S 中有 2n 个元素，从栈顶到栈底的元素依次为 a2n，a2n-1，…，a1，要求通过一个循环队列重新排列栈中元素，使得从栈顶到栈底的元素依次为 a2n，a2n-2，…，a2，a2n-1，a2n-3，…，a1，请设计算法实现该操作，要求空间复杂度和时间复杂度均为 O(n)。
3. 设计算法把一个十进制整数转换为二至九进制之间的任一进制数输出。
4. 假设一个算术表达式中可以包含三种括号：圆括号`(`和`)`，方括号`[`和`]`以及花括号`{`和`}`，且这三种括号可按任意的次序嵌套使用。编写算法判断给定表达式中所含括号是否配对出现。 
5. 对串的模式匹配**KMP算法**设计求模式滑动位置的`next()`函数。

## 第三部分 多维数组和广义表

1. 若在矩阵 A 中存在一个元素 ai,j（0≤i≤n-1，0≤j≤m-1），该元素是第 i 行元素中最小值且又是第 j 列元素中最大值，则称此元素为该矩阵的一个**马鞍点**。假设以二维数组存储矩阵 A，试设计一个求该矩阵所有马鞍点的算法，并分析最坏情况下的时间复杂度。 
2. 已知两个 n×n 的对称矩阵按压缩存储方法存储在一维数组 A 和 B 中，编写算法计算对称矩阵的乘积。 