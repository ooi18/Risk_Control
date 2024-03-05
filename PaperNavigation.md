# 顶会</br>

## KDD (Data Mining)
[2018-Adversarial Attacks on Neural Networks for Graph Data	Daniel Zügner-Technical University of Munich; et al.]()

[2026-FRAUDAR: Bounding Graph Fraud in the Face of Camouflage	Bryan Hooi-Carnegie Mellon University; et al.]()

[2012-Searching and Mining Trillions of Time Series Subsequences under Dynamic Time Warping-Thanawin Rakthanmanon, University of California, Riverside; et al.]()

[2004-A probabilistic framework for semi-supervised clustering-Sugato Basu, University of Texas at Austin; et al.]()

[2002-Pattern discovery in sequences under a Markov assumption-Darya Chudova & Padhraic Smyth, University of California, Irvine]()


## AAAI (Artificial Intelligence) NoProper
## NeurIPS (Machine Learning) NoProper
## ICML (Machine Learning)  NoProper
## IJCAI (Artificial Intelligence)  NoProper




- 有代码</br>
> SliceNDice：捕捉具备大量共同属性的用户，比如在同一时间和地点创建的帐户、宣传相同言论和转发类似文章的账户。(IEEE DSAA (2019)) 
> 输入：实体+属性1...+属性N
> 算法功能：根据共同属性构造边，合并各属性构造的子图，形成Multi-View Graph.随后挖掘异常关联子图（"dense" subnetwork）.
> 实验数据集大小：Snapchat advertiser platform（23W实体 × 12属性），发现2435异常实体，precision 89%
- [SliceNDice: Mining Suspicious Multi-attribute Entity Groups with Multi-view Graphs](https://arxiv.org/abs/1908.07087) [SliceNDice-代码](https://github.com/hamedn/SliceNDice)</br>

> FlowScope(AAAI 2020年)
> 输入：A（转账人）->M(中间人)->C(收款人)
> 算法功能：找到其中可能涉及洗钱的团伙
> 实验数据集大小：-
- [FlowScope: Spotting Money Laundering Based on Graphs](https://shenghua-liu.github.io/papers/aaai2020cr-flowscope.pdf) [FlowScope-代码](https://github.com/BGT-M/spartan2)</br>


这篇论文中，作者构建了两种图结构：异构图Xianyu Graph和同构图Comment Graph。


> 输入：
异构图 Xianyu Graph：
节点： 由用户（U）、物品（I）和评论（E）组成。

同构图 Comment Graph：
节点： 由评论（E）组成。
边： 表示相似的评论。通过构建近似KNN图算法，找到每个评论的K个最近邻居，从而形成同构图。


> 算法功能：
使用异构GCN对Xianyu Graph进行embedding
采用归纳GCN对Comment Graph进行embedding
采用TextCNN对评论文本进行embedding
一起输入到GCN-based Anti-Spam（GAS）模型，进行有监督分类。
- [Spam Review Detection with Graph Convolutional Networks](https://arxiv.org/abs/1908.10679 '阿里的论文 CIKM 2019') [Spam Review Detection with Graph Convolutional Networks-代码](https://github.com/safe-graph/DGFraud)</br>

> 算法功能：考虑设备聚合和活动聚合，构建图结构embedding进行分类。本质是图卷积网络的一种变体
> 效果：GBDT+Graph 方法与 GBDT+Node2Vec 方法相比效果相似，而 GCN 的效果优于 GBDT+Graph 和 GBDT+Node2Vec。
> 作者提出的 GEM 方法在多种方面都优于 GCN，因为它处理了异构设备类型，而 GCN 只能处理同质图，无法区分图中不同类型的节点。
> GEM 还使用每种节点类型的聚合操作，而不是标准化操作，因此更好地模拟了底层的聚合模式。
- [Heterogeneous Graph Neural Networks for Malicious Account Detection](https://dl.acm.org/doi/10.1145/3269206.3272010 'CIKM 2018')[Heterogeneous Graph Neural Networks for Malicious Account Detection-代码](https://github.com/safe-graph/DGFraud)</br>

- [CatchCore: Catching Hierarchical Dense Subtensor](https://shenghua-liu.github.io/papers/pkdd2019-catchcore.pdf) [catchcore-代码](https://github.com/wenchieh/catchcore/tree/master)</br>

-感兴趣</br>
- [No Place to Hide: Catching Fraudulent Entities in Tensors](https://arxiv.org/pdf/1810.06230.pdf)</br>
- [Fraud Detection with Density Estimation Trees](https://proceedings.mlr.press/v71/ram18a/ram18a.pdf)</br>
- [HiDDen: Hierarchical Dense Subgraph Detection with Application to Financial Fraud Detection](https://www.public.asu.edu/~hdavulcu/SDM17.pdf)</br>
- [FairPlay: Fraud and Malware Detection in Google Play](https://arxiv.org/abs/1703.02002)</br>
- [Fraud Transactions Detection via Behavior Tree with Local Intention Calibration](https://dl.acm.org/doi/abs/10.1145/3394486.3403354)</br>

-其它</br>
- [Identifying Anomalies in Graph Streams Using Change Detection](https://www.mlgworkshop.org/2016/paper/MLG2016_paper_12.pdf)</br>



- [HitFraud: A Broad Learning Approach for Collective Fraud Detection in Heterogeneous Information Networks](https://arxiv.org/abs/1709.04129)</br>
- [Friend or Faux: Graph-Based Early Detection of Fake Accounts on Social Networks](https://arxiv.org/abs/2004.04834)</br>

   
- 后续研究</br>
- [focus](https://github.com/BGT-M/spartan2 'spartan2 is a collection of data mining algorithms on big graphs and time series, providing three basic tasks: anomaly detection, forecast, and summarization.')



# 参考网站
[Awesome Fraud Detection Research Papers.](https://github.com/benedekrozemberczki/awesome-fraud-detection-papers '')
[Fraud Detection Papers](https://github.com/IPL/fraud-detection-papers '')
[Best Paper Awards](https://jeffhuang.com/best_paper_awards/institutions.html '')