# Document-Level-Relation-Extraction-Paper-List

[TOC]

## Published

ordered from new to old

### AAAI 2021

* [Document-Level Relation Extraction with Reconstruction](https://arxiv.org/abs/2012.11384), Wang Xu, Kehai Chen, Tiejun Zhao 

* [Document-Level Relation Extraction with Adaptive Thresholding and Localized Context Pooling](https://arxiv.org/abs/2010.11304), Wenxuan Zhou, Kevin Huang, Tengyu Ma, Jing Huang

* [Entity Structure Within and Throughout: Modeling Mention Dependencies for Document- Level Relation Extraction](), Benfeng Xu, Quan Wang, Yajuan Lyu, Yong Zhu, Zhendong Mao

* [Multi-view Inference for Relation Extraction with Uncertain Knowledge](https://www.researchgate.net/publication/347879225_Multi-view_Inference_for_Relation_Extraction_with_Uncertain_Knowledge), Bo Li, Wei Ye, Canming Huang, Shikun Zhang

### COLING 2020

* [Graph Enhanced Dual Attention Network for Document-Level Relation Extraction](https://www.aclweb.org/anthology/2020.coling-main.136/),Bo Li, Wei Ye, Zhonghao Sheng, Rui Xie, Xiangyu Xi, Shikun Zhang, COLING 2020
  <br> 👉 Method: bi-directional attn between sentence & relation instance + attn duality + support evidence guide

* [Global Context-enhanced Graph Convolutional Networks for Document-level Relation Extraction](https://www.aclweb.org/anthology/2020.coling-main.461/), Huiwei Zhou, Yibin Xu, Zhe Liu, Weihong Yao, Chengkun Lang, Haibin Jiang, COLING 2020
  <br> 👉 Method: entity graph with attn gate & attn adj matrix for entity representation + entity graph with multi-head attn as adj matrix for reasoning + dense-node&edge-GCN

* [Document-level Relation Extraction with Dual-tier Heterogeneous Graph](https://www.aclweb.org/anthology/2020.coling-main.143/), Zhenyu Zhang, Bowen Yu, Xiaobo Shu, Tingwen Liu, Hengzhu Tang, Yubin Wang and Li Guo, COLING 2020
  <br> 👉 Method: strcuct modeling graph + relation reasoning graph + weighted RGCN

### EMNLP 2020

* [Double Graph Based Reasoning for Document-level Relation Extraction](https://arxiv.org/abs/2009.13752), Shuang Zeng, Runxin Xu, Baobao Chang, Lei Li, EMNLP 2020
  <br> 👉 Method: Mention graph(mention + doc node) + entity graph (2-hot at most)

* [Global-to-Local Neural Networks for Document-Level Relation Extraction](https://www.aclweb.org/anthology/2020.emnlp-main.303), Difeng Wang, Wei Hu, Ermei Cao, Weijian Sun, EMNLP 2020
  <br> 👉 Method: EoG + R-GCN + entity-pair attention

* [Denoising Relation Extraction from Document-level Distant Supervision](https://arxiv.org/abs/2011.03888), Chaojun Xiao, Yuan Yao, Ruobing Xie, Xu Han, Zhiyuan Liu, Maosong Sun, Fen Lin, Leyu Lin, EMNLP 2020

### ACL 2020

* [Reasoning with Latent Structure Refinement for Document-Level Relation Extraction](https://arxiv.org/abs/2005.06312), Guoshun Nan, Zhijiang Guo, Ivan Sekulić, Wei Lu, ACL 2020
  <br> 👉 Method: Latent Structure + DCGCN

### EMNLP 2019

* [Connecting the Dots: Document-level Neural Relation Extraction with Edge-oriented Graphs](https://arxiv.org/abs/1909.00228), Fenia Christopoulou, Makoto Miwa, Sophia Ananiadou, EMNLP 2019
  <br> 👉 Method: Edge-oriented graph + Iterative Inference Mechanism

## arXiv / open review

### 2021

* [BERT-GT: Cross-sentence n-ary relation extraction with BERT and Graph Transformer](https://arxiv.org/abs/2101.04158), Po-Ting Lai, Zhiyong Lu
  <br> 👉 Method: densely connect Graph Transformer(neighbor attention) & Transformer to improve BERT

### Rejected by AAAI 2021

* [Coarse-to-Fine Entity Representations for Document-level Relation Extraction](https://arxiv.org/abs/2012.02507), Damai Dai, Jing Ren, Shuang Zeng, Baobao Chang, Zhifang Sui
  <br> 👉 Method: a word graph for coarse representation, Bi-GRU for path encoding, and an attention aggregator

* [Entity and Evidence Guided Relation Extraction for DocRED](https://arxiv.org/abs/2008.12283), Kevin Huang, Guangtao Wang, Tengyu Ma, Jing Huang

### 2019

* [Fine-tune Bert for DocRED with Two-step Process](https://arxiv.org/abs/1909.11898), Hong Wang, Christfried Focke, Rob Sylvester, Nilesh Mishra, William Wang

## TODOS

从标题上看，和 docRE 至少有弱联系的

#### 2020

* Tang, H.; Cao, Y.; Zhang, Z.; Cao, J.; Fang, F.; Wang, S.; and Yin, P. 2020. HIN: Hierarchical Inference Network for Document-Level Relation Extraction. In PAKDD 2020, vol- ume 12084 of Lecture Notes in Computer Science, 197–209.
* Deming Ye, Yankai Lin, Jiaju Du, Zhenghao Liu, Maosong Sun, and Zhiyuan Liu. 2020. Coreferential reasoning learning for language representation. In EMNLP, Online. ACL.
* Kuekyeng Kim, YunaHur, Gyeongmin Kim, and Heuiseok Lim. 2020. GREG: A Global Level Relation Extraction with Knowledge Graph Embedding. Applied Sciences, 10(3):1181.
* Angrosh Mandya, Danushka Bollega, and Frans Coenen. 2020. Contextualised Graph Attention for Improved Relation Extraction. arXiv:2004.10624.

#### 2019

* Robin Jia, Cliff Wong, and Hoifung Poon. 2019. Document-level n-ary relation extraction with mul- tiscale representation learning. In Proceedings of the 2019 Conference of the North American Chap- ter of the Association for Computational Linguistics, pages 3693–3704.
* Gupta, P.; Rajaram, S.; Schu ̈tze, H.; and Runkler, T. A. 2019. Neural Relation Extraction within and across Sen- tence Boundaries. In AAAI 2019, 6513–6520.
* Zhijiang Guo, Yan Zhang, and Wei Lu. Atten- tion guided graph convolutional networks for rela- tion extraction. ACL 2019
* Sunil Kumar Sahu, Fenia Christopoulou, Makoto Miwa, and Sophia Ananiadou. 2019. Inter-sentence relation extraction with document-level graph con- volutional neural network. ACL 2019
* Ningyu Zhang, Shumin Deng, Zhanlin Sun, Guanying Wang, Xi Chen, Wei Zhang, and Huajun Chen. 2019. Long-tail relation extraction via knowledge graph embeddings and graph convolution networks. In NAACL-HLT, pages 3016–3025, Minneapolis, MN, USA. ACL.
* Ming Tu, Guangtao Wang, Jing Huang, Yun Tang, Xi- aodong He, and Bowen Zhou. 2019. Multi-hop read- ing comprehension across multiple documents by reasoning over heterogeneous graphs. In Proc. of ACL.
* Bill Yuchen Lin, Xinyue Chen, Jamin Chen, and Xi- ang Ren. 2019. Kagnet: Knowledge-aware graph networks for commonsense reasoning. In Proc. of EMNLP.
* Nicola De Cao, Wilker Aziz, Ivan Titov. Question Answering by Reasoning Across Documents with Graph Convolutional Networks. NAACL 2019.
* Yu Cao, Meng Fang, and Dacheng Tao. 2019. Bag: Bi-directional attention entity graph convolutional network for multi-hop reasoning question answering. In Proc. of NAACL.
* Hao Zhu, Yankai Lin, Zhiyuan Liu, Jie Fu, Tat-seng Chua, and Maosong Sun. 2019. Graph Neural Networks with Generated Parameters for Relation Extraction. ACL 2019


#### 2018

* Linfeng Song, Yue Zhang, Zhiguo Wang, and Daniel Gildea. 2018c. N-ary relation extraction using graph state lstm. In Proc. of EMNLP.
* Patrick Verga, Emma Strubell, and Andrew McCallum. 2018. Simultaneously self-attending to all mentions for full-abstract biological relation extraction. In Proc. of NAACL-HLT.
* Yuhao Zhang, Peng Qi, and Christopher D Manning. 2018. Graph convolution over pruned dependency trees improves relation extraction. In EMNLP, pages 2205–2215, Brussels, Belgium. ACL.
* Wei Zheng, Hongfei Lin, Zhiheng Li, Xiaoxia Liu, Zhengguang Li, Bo Xu, Yijia Zhang, Zhihao Yang, and Jian Wang. 2018. An effective neural model extracting document level chemical-induced disease relations from biomedical literature. Journal of Biomedical Informatics, 83:1–9.
* Rasmus Palm, Ulrich Paquet, Ole Winther. Recurrent Relational Networks. NeurIPS 2018.
* Dat Quoc Nguyen and Karin Verspoor. Convolutional neural networks for chemical-disease relation ex- traction are improved with character-based word embeddings. BioNLP 2018



#### Earlier

* Nanyun Peng, Hoifung Poon, Chris Quirk, Kristina Toutanova, and Wen-tau Yih. 2017. Cross-sentence n-ary relation extraction with graph LSTMs. Trans- actions of the Association for Computational Lin- guistics, 5:101–115.
* Chris Quirk and Hoifung Poon. 2017. Distant super- vision for relation extraction beyond the sentence boundary. In Proceedings of the 15th Conference of the European Chapter of the Association for Compu- tational Linguistics: Volume 1, Long Papers, pages 1171–1182.
* Wenyuan Zeng, Yankai Lin, Zhiyuan Liu, and Maosong Sun. 2017. Incorporating relation paths in neural relation extraction. In Proceedings of the Conference on Empirical Methods in Natural Lan- guage Processing, pages 1768–1777. Association for Computational Linguistics.
