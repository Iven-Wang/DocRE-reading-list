
This is a paper reading list on Document level Relation Extraction.

Our list is still incomplete and the categorization might be inappropriate. We will keep adding papers and improving the list. Any suggestions are welcomed!

## Doc RE Papers

### 2021

* EACL 2021 [An End-to-end Model for Entity-level Relation Extraction using Multi-instance Learning](https://arxiv.org/abs/2102.05980), Markus Eberts, Adrian Ulges
  <br> 👉 Method: a model for JOINT mention detection and doc RE: finetune BERT for 4 tasks: entity mention localization, coreference resolution, entity classification and relation classification

* AAAI 2021 [Document-Level Relation Extraction with Reconstruction](https://arxiv.org/abs/2012.11384), Wang Xu, Kehai Chen, Tiejun Zhao
  <br> 👉 Method: build a graph like EoG, use LSTM to calculate the probability of "inference meta path", then maximize the probability of relationed entity pairs using BCE

* AAAI 2021 [Document-Level Relation Extraction with Adaptive Thresholding and Localized Context Pooling](https://arxiv.org/abs/2010.11304), Wenxuan Zhou, Kevin Huang, Tengyu Ma, Jing Huang
  <br> 👉 Method: improve BERT with marker, log-sum-exp pooling, group bilinear + adaptive threshold class + directly use transformer's attn matrix to aggregation words into doc representation

* AAAI 2021 Entity Structure Within and Throughout: Modeling Mention Dependencies for Document-Level Relation Extraction, Benfeng Xu, Quan Wang, Yajuan Lyu, Yong Zhu, Zhendong Mao

* AAAI 2021 [Multi-view Inference for Relation Extraction with Uncertain Knowledge](https://www.researchgate.net/publication/347879225_Multi-view_Inference_for_Relation_Extraction_with_Uncertain_Knowledge), Bo Li, Wei Ye, Canming Huang, Shikun Zhang
  <br> 👉 Method: use KG concept knowledges: 3 attention aggregation(e2c, c2e, m2e) to get contextual and global entity pair representation, another attention aggregation to get sentence representation, concat for final classification

* arXiv 2021 [BERT-GT: Cross-sentence n-ary relation extraction with BERT and Graph Transformer](https://arxiv.org/abs/2101.04158), Po-Ting Lai, Zhiyong Lu
  <br> 👉 Method: densely connect Graph Transformer(neighbor attention) & Transformer to improve BERT

* arXiv 2021 [MrGCN: Mirror Graph Convolution Network for Relation Extraction with Long-Term Dependencies](http://arxiv.org/abs/2101.00124), Xiao Guo, I-Hung Hsu, Wael AbdAlmageed, Premkumar Natarajan, Nanyun Peng
  <br> 👉 Method: pooling-unpooling after GCN layers to enlarge receptive field (like u-net)


### 2020

* ACL 2020 [Reasoning with Latent Structure Refinement for Document-Level Relation Extraction](https://arxiv.org/abs/2005.06312), Guoshun Nan, Zhijiang Guo, Ivan Sekulić, Wei Lu
  <br> 👉 Method: Latent Structure + DCGCN

* EMNLP 2020 [Double Graph Based Reasoning for Document-level Relation Extraction](https://arxiv.org/abs/2009.13752), Shuang Zeng, Runxin Xu, Baobao Chang, Lei Li
  <br> 👉 Method: Mention graph(mention + doc node) + entity graph (2-hot at most)

* EMNLP 2020 [Global-to-Local Neural Networks for Document-Level Relation Extraction](https://www.aclweb.org/anthology/2020.emnlp-main.303), Difeng Wang, Wei Hu, Ermei Cao, Weijian Sun
  <br> 👉 Method: EoG + R-GCN + entity-pair attention

* EMNLP 2020 [Denoising Relation Extraction from Document-level Distant Supervision](https://arxiv.org/abs/2011.03888), Chaojun Xiao, Yuan Yao, Ruobing Xie, Xu Han, Zhiyuan Liu, Maosong Sun, Fen Lin, Leyu Lin
  <br> 👉 Method: using DS data to pre-train model for DocRE with 3 tasks: Mention-Entity Matching, Relation Detection, Relational Fact Alignment

* COLING 2020 [Graph Enhanced Dual Attention Network for Document-Level Relation Extraction](https://www.aclweb.org/anthology/2020.coling-main.136/),Bo Li, Wei Ye, Zhonghao Sheng, Rui Xie, Xiangyu Xi, Shikun Zhang
  <br> 👉 Method: bi-directional attn between sentence & relation instance + attn duality + support evidence guide

* COLING 2020 [Global Context-enhanced Graph Convolutional Networks for Document-level Relation Extraction](https://www.aclweb.org/anthology/2020.coling-main.461/), Huiwei Zhou, Yibin Xu, Zhe Liu, Weihong Yao, Chengkun Lang, Haibin Jiang
  <br> 👉 Method: entity graph with attn gate & attn adj matrix for entity representation + entity graph with multi-head attn as adj matrix for reasoning + dense-node&edge-GCN

* COLING 2020 [Document-level Relation Extraction with Dual-tier Heterogeneous Graph](https://www.aclweb.org/anthology/2020.coling-main.143/), Zhenyu Zhang, Bowen Yu, Xiaobo Shu, Tingwen Liu, Hengzhu Tang, Yubin Wang and Li Guo
  <br> 👉 Method: strcuct modeling graph + relation reasoning graph + weighted RGCN

* PAKDD 2020 [HIN: Hierarchical Inference Network for Document-Level Relation Extraction](https://arxiv.org/abs/2003.12754), Hengzhu Tang, Yanan Cao, Zhenyu Zhang, Jiangxia Cao, Fang Fang, Shi Wang, Pengfei Yin
  <br> 👉 Method: Hierarchical (entity & document level) inference representation (using LSTMs, attention and all kinds of "concat") for an entity pair's representation

* arXiv 2020 [Coarse-to-Fine Entity Representations for Document-level Relation Extraction](https://arxiv.org/abs/2012.02507), Damai Dai, Jing Ren, Shuang Zeng, Baobao Chang, Zhifang Sui
  <br> 👉 Method: a word graph for coarse representation, Bi-GRU for path encoding, and an attention aggregator

* arXiv 2020 [Entity and Evidence Guided Relation Extraction for DocRED](https://arxiv.org/abs/2008.12283), Kevin Huang, Guangtao Wang, Tengyu Ma, Jing Huang
  <br> 👉 Method: convert a doc into N {head entity; doc} samples for BERT, bilinear for RE, and double bilinear for evidence prediction as an auxiliary task

* IEEE Access 2020 [A Novel Document-Level Relation Extraction Method Based on BERT and Entity Information](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9098945), Xiaoyu Han and Lei Wang
  <br> 👉 Method: using marker to wrap mention as {[entity type] mention [entity X]}, then using BERT + bilinear

### 2019

* ACL 2019 [Inter-sentence Relation Extraction with Document-level Graph Convolutional Neural Network](https://www.aclweb.org/anthology/P19-1423/), Sunil Kumar Sahu, Fenia Christopoulou, Makoto Miwa, and Sophia Ananiadou
  <br> 👉 Method: GCN + bi-affine classification

* ACL 2019 [Attention Guided Graph Convolutional Networks for Relation Extraction](https://www.aclweb.org/anthology/P19-1024.pdf), Zhijiang Guo, Yan Zhang, Wei Lu
  <br> 👉 Method: multi-head attention to get multi graph with different adj matrix + dense GCN

* EMNLP 2019 [Connecting the Dots: Document-level Neural Relation Extraction with Edge-oriented Graphs](https://arxiv.org/abs/1909.00228), Fenia Christopoulou, Makoto Miwa, Sophia Ananiadou, EMNLP 2019
  <br> 👉 Method: Edge-oriented graph + Iterative Inference Mechanism

* NAACL 2019 [Document-Level N-ary Relation Extraction with Multiscale Representation Learning](https://arxiv.org/abs/1904.02347), Robin Jia, Cliff Wong, Hoifung Poon
  <br> 👉 Method: multioscale representation of mention and entity: lstm for paragraph-level mention representation, log-sum-exp pooling for entity representation

* arXiv 2019 [Fine-tune Bert for DocRED with Two-step Process](https://arxiv.org/abs/1909.11898), Hong Wang, Christfried Focke, Rob Sylvester, Nilesh Mishra, William Wang
  <br> 👉 Method: BERT + bilinear, 2 step training: binary classification for relation detection, then multi classification for relation type

### 2018

* NAACL 2018 [Simultaneously Self-Attending to All Mentions for Full-Abstract Biological Relation Extraction](https://www.aclweb.org/anthology/N18-1080/), Patrick Verga, Emma Strubell, and Andrew McCallum


## Related Papers

The task of those papers are somewhat relevant to Doc RE (i.e. cross-sentence RE, GCN for RE, reasoning for MRC, etc.), of much value as well

### 2021

* EACL 2021 [Two Training Strategies for Improving Relation Extraction over Universal Graph](https://arxiv.org/abs/2102.06540), Qin Dai, Naoya Inoue, Ryo Takahashi and Kentaro Inui
  <br> 👉 Task: DSRE
  <br> 👉 Method: merge text into KG, and improve the "select path" stage with path type (textual, hybrid, KG paths) adaptive pretraining & complexity ranking guided attention

### 2019

* ACL 2019 [Multi-hop reading comprehension across multiple documents by reasoning over heterogeneous graphs](https://www.aclweb.org/anthology/P19-1260.pdf), Ming Tu, Guangtao Wang, Jing Huang, Yun Tang, Xiaodong He, and Bowen Zhou

* ACL 2019 [Graph Neural Networks with Generated Parameters for Relation Extraction](https://www.aclweb.org/anthology/P19-1128.pdf), Hao Zhu, Yankai Lin, Zhiyuan Liu, Jie Fu, Tat-seng Chua, and Maosong Sun

* EMNLP 2019 [KagNet: Knowledge-Aware Graph Networks for Commonsense Reasoning](https://www.aclweb.org/anthology/D19-1282.pdf), Bill Yuchen Lin, Xinyue Chen, Jamin Chen, and Xiang Ren

* NAACL 2019 [Question Answering by Reasoning Across Documents with Graph Convolutional Networks](https://arxiv.org/abs/1808.09920), Nicola De Cao, Wilker Aziz, Ivan Titov

* NAACL 2019 [BAG: Bi-directional Attention Entity Graph Convolutional Network for Multi-hop Reasoning Question Answering](https://arxiv.org/abs/1904.04969), Yu Cao, Meng Fang, and Dacheng Tao

* NAACL 2019 [Long-tail relation extraction via knowledge graph embeddings and graph convolution networks](https://www.aclweb.org/anthology/N19-1306.pdf), Ningyu Zhang, Shumin Deng, Zhanlin Sun, Guanying Wang, Xi Chen, Wei Zhang, and Huajun Chen
  <br> 👉 Task: RE
  <br> 👉 Method: Using KG knowledges to improve the performance of long-tail instances in RE. Using KG embeddings and GCN to learn relational knowledge, then attention aggregation to get final relation representation

* AAAI 2019 [Neural Relation Extraction within and across Sentence Boundaries](https://arxiv.org/abs/1810.05102), Pankaj Gupta, Subburam Rajaram, Bernt Andrassy, Hinrich Schutze, Thomas Runkler
  <br> 👉 Task: cross sentence RE
  <br> 👉 Method: Using RNN to model the dependancy subtree

### 2018

* EMNLP 2018 [N-ary Relation Extraction using Graph-State LSTM](https://www.aclweb.org/anthology/D18-1246), Linfeng Song, Yue Zhang, Zhiguo Wang, and Daniel Gildea

* EMNLP 2018 [Graph Convolution over Pruned Dependency Trees Improves Relation Extraction](https://www.aclweb.org/anthology/D18-1244/), Yuhao Zhang, Peng Qi, and Christopher D Manning

* Wei Zheng, Hongfei Lin, Zhiheng Li, Xiaoxia Liu, Zhengguang Li, Bo Xu, Yijia Zhang, Zhihao Yang, and Jian Wang. 2018. An effective neural model extracting document level chemical-induced disease relations from biomedical literature. Journal of Biomedical Informatics, 83:1–9.

* NeurIPS 2018 [Recurrent Relational Networks](https://arxiv.org/abs/1711.08028), Rasmus Palm, Ulrich Paquet, Ole Winther

* ACL 2018 [A Walk-based Model on Entity Graphs for Relation Extraction](https://www.aclweb.org/anthology/P18-2014/), Fenia Christopoulou, Makoto Miwa, Sophia Ananiadou

### 2017

* TACL 2017 [Cross-Sentence N-ary Relation Extraction with Graph LSTMs](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/tacl17.pdf), Nanyun Peng, Hoifung Poon, Chris Quirk, Kristina Toutanova, and Wen-tau Yih

* ACL 2017 [Distant Supervision for Relation Extraction beyond the Sentence Boundary](https://www.aclweb.org/anthology/E17-1110), Chris Quirk and Hoifung Poon. 

* EMNLP 2017 [Incorporating relation paths in neural relation extraction](https://www.aclweb.org/anthology/D17-1186), Wenyuan Zeng, Yankai Lin, Zhiyuan Liu, and Maosong Sun
