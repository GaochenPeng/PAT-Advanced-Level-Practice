# Summary
使用左孩子右兄弟表示法  
在计算层数的同时使用static的map记录叶子节点数量  

注意：
1. n可能是0 (测试点中好像没出现。。)  
2. n=1, m=0时输出1 (我被这个坑了，因为没有m就没有构造多叉树，直接输出0. 刚开始一个测试点怎么都过不去。。。)
3. 节点不一定按着顺序来  