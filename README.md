# deep-learning-sort-guide
use to manage paper

[有什么好的深度学习领域的分类方式吗？ - 知乎](https://www.zhihu.com/question/438493266)

单独从某一角度出发，实际上比较容易完成对领域的分类，但不同的论文，侧重点是不同的，多视角的元信息标注是必要的。

此时，如果全部是标签固然可行，但标签一多就会导致管理问题；而如果是分类树，就会因为多视角导致类别交叉。

理论上一个比较良好的管理方式应该是分类树加层次标签，但大多数管理软件（我主要用的是 zotero，开源万岁）似乎也没有层次标签这个概念，都是分类树＋单标签。但即便是分类树+多标签，应该也能够在一定妥协的情况下实现完整的分类管理。

因此，从什么角度出发建立分类树，从什么角度出发添加标签，能使得最终搜索起来对用户最友好？这是一个寻找局部最优解的问题。



## 从标签质量和对标签的利用程度区分

 - 有监督
 - 弱监督
    - 不准确监督（Noisy Label）
    - 不完全监督
      - 半监督
      - 主动学习
  - 无监督
    - 自监督
    - 聚类
   
   
## 从应用领域分

 - NLP
 - CV
 - ...
 
## 从流程区分
 
 - 数据
   - 数据集
   - 数据增广
 - 模型
 - 目标函数
 - 优化器
 - 算法
 
 
