# Document-Level-Relation-Extraction-Paper-List


## Graph Based

1. [Connecting the Dots: Document-level Neural Relation Extraction with Edge-oriented Graphs](https://arxiv.org/abs/1909.00228), Fenia Christopoulou, Makoto Miwa, Sophia Ananiadou, EMNLP 2019
* Method: Edge-oriented graph + Iterative Inference Mechanism

2. [Reasoning with Latent Structure Refinement for Document-Level Relation Extraction](https://arxiv.org/abs/2005.06312), Guoshun Nan, Zhijiang Guo, Ivan Sekulić, Wei Lu, ACL 2020
* Method: Latent Structure + DCGCN

3. [Double Graph Based Reasoning for Document-level Relation Extraction](https://arxiv.org/abs/2009.13752), Shuang Zeng, Runxin Xu, Baobao Chang, Lei Li, EMNLP 2020
* Method: Mention graph(mention + doc node) + entity graph (2-hot at most)

4. [Global-to-Local Neural Networks for Document-Level Relation Extraction](https://www.aclweb.org/anthology/2020.emnlp-main.303), Difeng Wang, Wei Hu†, Ermei Cao, Weijian Sun, EMNLP 2020
* Method: EoG + R-GCN + entity-pair attention

5. [Coarse-to-Fine Entity Representations for Document-level Relation Extraction](https://arxiv.org/abs/2012.02507), Damai Dai, Jing Ren, Shuang Zeng, Baobao Chang, Zhifang Sui, arXiv 4 Dec 2020
* Method: a word graph for coarse representation, Bi-GRU for path encoding, and an attention aggregator

6. [Graph Enhanced Dual Attention Network for Document-Level Relation Extraction](https://www.aclweb.org/anthology/2020.coling-main.136/),Bo Li, Wei Ye, Zhonghao Sheng, Rui Xie, Xiangyu Xi, Shikun Zhang, COLING 2020


7. [Global Context-enhanced Graph Convolutional Networks for Document-level Relation Extraction](https://www.aclweb.org/anthology/2020.coling-main.461/), Huiwei Zhou, Yibin Xu, Zhe Liu, Weihong Yao, Chengkun Lang, Haibin Jiang, COLING 2020

8. [Document-level Relation Extraction with Dual-tier Heterogeneous Graph](https://www.aclweb.org/anthology/2020.coling-main.143/), Zhenyu Zhang, Bowen Yu, Xiaobo Shu, Tingwen Liu, Hengzhu Tang, Yubin Wang and Li Guo, COLING 2020


## BERT Based

* Hong Wang, Christfried Focke, Rob Sylvester, Nilesh Mishra, and William Wang. 2019. Fine-tune bert for docred with two-step process. arXiv preprint arXiv:1909.11898.

## Sequence Based



## TODOS

从标题上看，和 docRE 至少有弱联系的

#### 2020

* Tang, H.; Cao, Y.; Zhang, Z.; Cao, J.; Fang, F.; Wang, S.; and Yin, P. 2020. HIN: Hierarchical Inference Network for Document-Level Relation Extraction. In PAKDD 2020, vol- ume 12084 of Lecture Notes in Computer Science, 197–209.
* Deming Ye, Yankai Lin, Jiaju Du, Zhenghao Liu, Maosong Sun, and Zhiyuan Liu. 2020. Coreferen- tial reasoning learning for language representation. In EMNLP, Online. ACL.


#### 2019

* Robin Jia, Cliff Wong, and Hoifung Poon. 2019. Document-level n-ary relation extraction with mul- tiscale representation learning. In Proceedings of the 2019 Conference of the North American Chap- ter of the Association for Computational Linguistics, pages 3693–3704.
* Gupta, P.; Rajaram, S.; Schu ̈tze, H.; and Runkler, T. A. 2019. Neural Relation Extraction within and across Sen- tence Boundaries. In AAAI 2019, 6513–6520.
* Zhijiang Guo, Yan Zhang, and Wei Lu. Atten- tion guided graph convolutional networks for rela- tion extraction. ACL 2019
* Sunil Kumar Sahu, Fenia Christopoulou, Makoto Miwa, and Sophia Ananiadou. 2019. Inter-sentence relation extraction with document-level graph con- volutional neural network. In Proceedings of the 57th Annual Meeting of the Association for Compu- tational Linguistics, pages 4309–4316.
* Ningyu Zhang, Shumin Deng, Zhanlin Sun, Guanying Wang, Xi Chen, Wei Zhang, and Huajun Chen. 2019. Long-tail relation extraction via knowledge graph embeddings and graph convolution networks. In NAACL-HLT, pages 3016–3025, Minneapolis, MN, USA. ACL.
* Nicola De Cao, Wilker Aziz, and Ivan Titov. 2019. Question answering by reasoning across documents with graph convolutional networks. In Proc. of NAACL-HLT.

#### 2018

* Song, L.; Zhang, Y.; Wang, Z.; and Gildea, D. 2018. N-ary Relation Extraction using Graph-State LSTM. In EMNLP 2018, 2226–2235.
* Patrick Verga, Emma Strubell, and Andrew McCallum. 2018. Simultaneously self-attending to all mentions for full-abstract biological relation extraction. In Proc. of NAACL-HLT.
* Yuhao Zhang, Peng Qi, and Christopher D Manning. 2018. Graph convolution over pruned dependency trees improves relation extraction. In EMNLP, pages 2205–2215, Brussels, Belgium. ACL.
* Wei Zheng, Hongfei Lin, Zhiheng Li, Xiaoxia Liu, Zhengguang Li, Bo Xu, Yijia Zhang, Zhihao Yang, and Jian Wang. 2018. An effective neural model extracting document level chemical-induced disease relations from biomedical literature. Journal of Biomedical Informatics, 83:1–9.


#### Earlier

* Nanyun Peng, Hoifung Poon, Chris Quirk, Kristina Toutanova, and Wen-tau Yih. 2017. Cross-sentence n-ary relation extraction with graph LSTMs. Trans- actions of the Association for Computational Lin- guistics, 5:101–115.
* Chris Quirk and Hoifung Poon. 2017. Distant super- vision for relation extraction beyond the sentence boundary. In Proceedings of the 15th Conference of the European Chapter of the Association for Compu- tational Linguistics: Volume 1, Long Papers, pages 1171–1182.
* Wenyuan Zeng, Yankai Lin, Zhiyuan Liu, and Maosong Sun. 2017. Incorporating relation paths in neural relation extraction. In Proceedings of the Conference on Empirical Methods in Natural Lan- guage Processing, pages 1768–1777. Association for Computational Linguistics.
