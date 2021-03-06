---
topic: 贪心算法原理
date: 2017/10/19
labels: 最优子结构，贪心策略
---
贪心算法的原理就是通过做出一系列的选择来求出问题的最优解。在面临每一个选择时，必须选择当前是最好的或者是最有利的选择，但是这种选择导致最后可能没有办法得到解。但是，不能否定的是贪心策略确实可以帮助我们在某些情况下找到最优解。

###步骤
1. 确定问题的最优子结构
2. 设计一个递归算法
3. 证明如果我们做出选择的话，则只剩下一个子问题。
4. 证明贪心选择总是安全的
5. 设计一个递归算法实现贪心策略。
6. 将递归算法转化为迭代算法。

贪心算法是以动态规划方法为基础的。

---
2017/10/20更新
我们应该知道，每一个贪心算法都可以有一个更繁琐的动态规划算法。

###贪心选择性质
通过做出局部最优解（贪心）选择来构造全局最优解。换句话说，我们直接做出在当前问题看起来是最优的选择，而不必考虑子问题的解。

**这也是贪心算法和动态规划的不同之处**，动态规划每个步骤都要进行一次选择，但选择通常依赖于子问题的解。因此，**我们通常以一种自底向下的方式求解动态规划问题。**

在贪心算法中，**我们总是做出当时看来最佳的选择，然后求解剩下的唯一的子问题**。

贪心算法进行选择时可能依赖之前做出的选择，但不依赖任何将来的选择或子问题的解。因此，与动态规划先求解子问题才能第一次选择不同，贪心算法在进行第一次选择之前不求解任何子问题。

一个动态规划算法是自底向上进行计算的，而一个贪心算法通常是自顶向下的，进行一次又一次选择，将给定问题实例变得更小。

###最优子结构
如果一个问题的最优解包含其子问题的最优解，则称此问题具有最优子结构性质。此性质是能否应用动态规划和贪心算法的关键要素。

###贪心对动态规划
0-1背包问题（0-1 knapsack problem）使用贪心算法不一定可以达到最优解，而分数背包问题（fractional knapsack problem）可以使用贪心策略。

---

