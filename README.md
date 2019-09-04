# 知识梳理
## 算法
- ### 理论基础
    - #### 复杂度分析
    - [ ] 极客时间-王争  03 | 复杂度分析（上）：如何分析、统计算法的执行效率和资源消耗？
    - [ ] 极客时间-王争  04 | 复杂度分析（下）：浅析最好、最坏、平均、均摊时间复杂度
    - [ ] 极客时间-覃超  03 | 如何计算算法的复杂度
          <details>
           <summary>主定理</summary>
            <p>二分查找 O(logn)</p>
            <p>二叉树遍历 O(n)</p>
            <p>归并排序 O(nlogn)</p>
          </details>
          <details>
           <summary>切题四件套</summary>
          </details>
## 分布式系统架构
- ### 理论基础
    - [ ] [左耳听风 28. 推荐阅读 分布式系统架构经典资料](https://time.geekbang.org/column/article/2080)
    - [ ] [Distributed systems theory for the distributed systems engineer](https://www.the-paper-trail.org/post/2014-08-09-distributed-systems-theory-for-the-distributed-systems-engineer/)
    - [ ] [CAP confusion: Problems with Partition Tolerance](https://www.the-paper-trail.org/post/2014-08-09-distributed-systems-theory-for-the-distributed-systems-engineer/)
      <details>
      <summary>CAP理解误区</summary>
          <p align="left"> 
              CAP中的P不是一种可选的能力，而是一个有一定概率会发生的事件，我们需要回答的问题是当网络分区这个事件发生之后，我们的系统要保证一致性C还是可用性A，保证一致性就必须牺牲数据的写入（牺牲可用性），而保留可用性就要容忍数据的不一致。如果有人说他的系统是CA的，那么他其实并没有搞懂CAP理论，你可以问他之前那个问题，当网络分区发生之后，他的系统会如何应对，如果他说系统不能再继续操作，那么是他的系统其实是CP，如果他说可以响应部分操作但是可能读不到最新的数据，那么是AP。
          </p>
          <p align="left"> 
          另外，CAP中的C和ACID中的C也完全不是一回事，下次有时间再说。
          </p>
      </details>
