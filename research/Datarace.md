## 做的事情(全天时间花在：论文阅读方式处理)

---

- 阅读论文****Real-world Go Concurrency Bugs by Changkun****
    - [PPT](https://docs.google.com/presentation/d/1clppbBqjxzPrj-26d_zVeJK2fFiXCsNVXYhKPjEZ4Tc/edit#slide=id.g41b9834bc3_0_0)
    - [YOUTUBE](https://www.youtube.com/watch?v=WZUii-Czaps)
    
- 尝试阅读 ThreadSanitizer – data race detection in practice


---

## ThreadSanitizer

- alg
    - happen-before
    - locksets
    - 本质：分布式算法向量时钟
- go的数据竞争检测器

## 思考

---

- 强制自己每天输出，是否可行啊
- 没有产出的一天
- 遇到问题，可以记录，但是不要被带偏
- 如果有优先级非常高的任务，可以做抢占调度，任务排期可以做往后靠
- 如果在排期过程中碰到的new idea or problem or something you’re interested ,你应该mark 而不是阻塞主线程，开新的g去处理这些事情
