# Unity-Shader-
一个菜鸟的第一步
## 渲染流水线
重点:科目一考试的前一天软件能力认证中心应用号会推送案例，推送的案例有概率和考试题题型类似因此务必把这两道题搞清楚!!!!!

可信考试三道题过两道基本必过，题目主要有以下几种形式

一题：设计题/字符串/位运算/排序/其他，一般可根据题意按步骤实现暴力通过

二题:  设计题/算法题，算法主要常见类型包括DFS，双指针，树类，贪心，哈希表优化，偶尔涉及优先队列，栈等

三题: 算法题，算法图类，树类题最多，可能涉及并查集，拓扑排序，BFS, DFS，回溯等

第三题一般理解题意较为容易，主要适合leetcode基础好的同学尝试，有时候会存在模板题，之前认证题目就出现过第三题使用BFS模板稍作改动即可通过的情况。如果leetcode400+这种情况下很可能比二题更容易AC。

一题+二题是大多数人的选择，算法难度比leetcode要低，但是题目比leetcode长，条件较多需要认真读题。

一般题目存在以下几种搭配方式：

1 一题设计+二题算法， 这种情况下相对比较好通过，设计题较为简单，通常按题意按步就班写完即可。二题算法题暴力只能通过部分用例，需要稍作优化

2  二题设计， 这种情况下设计题会较为复杂，之前认证题目有过设计题需要结合DFS的情况。一题如果是贪心排序这类会比较简单，字符串类翻车可能较大，遗漏条件或是不熟悉某种字符串操作都会导致翻车


下面针对Python语言提几个建议：

1 设计类题目：

最重要的是选好适合的容器，一般无非下面几种：

字典嵌套字典，字典嵌套列表，列表，Set

因此一个建议是熟练使用defaultdict，只要是字典嵌套的场景defaultdict可以无脑用！！！defaultdict能够有效避免keyerror对于操作简化十分有效，并且除了初始化和import以外使用方式和字典相同，几乎没有任何学习成本。关于defaultdict的好处大家可以在下面认证题目中体会

2 算法类：

二题的算法没有特别复杂的，优先考虑哈希表/排序，当你在考虑使用其他数据结构的时候80%可能你把问题复杂化了。

一定要熟练使用lambda表达式，特别是关于元组类的排序会经常用到


备战准备：

强烈建议使用认证题目做练习，特别一题和二题就像上面说的和leetcode上的题目区别较大，很多题目其实就是之前的认证题目的变形题甚至接近原题

附件里附上了我练习过的认证题目代码，总共有二十多道，主要涵盖设计题和二题三题的算法。不一定是最简单的实现但是比较通俗易懂的实现(基本都是借鉴认证开放中大佬们的代码)
