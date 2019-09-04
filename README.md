# 知识梳理
## 算法
- ### 理论基础
    - 算法面试通关40讲
    - [ ] 理论讲解：数组和链表
    - [ ] 反转一个单链表 & 判断链表是否循环

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
