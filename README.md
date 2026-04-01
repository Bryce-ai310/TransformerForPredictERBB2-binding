	#基于 CNN-Transformer 架构的 ERBB2抑制剂亲和力预测模型

1. data download and clean
   chEMPL下载ERBB2抑制剂IC50数据，去除空白smile，重复化合物数据IC50取中位数。

2.ERBB2是一种激酶（Kinase）。在真实的药物研发中，小分子激酶抑制剂（比如上市的拉帕替尼、图卡替尼）几乎 100% 都有复杂的芳香环结构，因为它们需要靠母核的环系去结合靶点蛋白底部的 ATP 结合口袋（Hinge Region）。因此需要去除掉没有骨架的药化分子。
