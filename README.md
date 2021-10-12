

# Must-read Papers on Sememe Computation

![](https://img.shields.io/github/last-commit/thunlp/SCPapers?color=blue)![](https://img.shields.io/badge/PaperNumber-53-brightgreen)![](https://img.shields.io/badge/PRs-Welcome-red) 

Contributed by [Fanchao Qi](https://github.com/Fanchao-Qi).

## Introduction

A **sememe** is defined as the minimum semantic unit in linguistics. Some linguists believe that meanings of all words can be decomposed of a limited set of sememes. 

Sememes can help us comprehend human languages better. Some studies have proved that neural NLP models benefit from the incorporation of sememes.

HowNet is the most famous sememe-based  knowledge base. It predefines a set of 2,000 sememes and uses them to annotate over 100,000 Chinese and English words.

[OpenHowNet](https://github.com/thunlp/OpenHowNet), developed by [THUNLP](http://nlp.csai.tsinghua.edu.cn/site2/index.php/en), opens source core data of HowNet and provides convenient data access APIs.


## Papers
### Introduction
1. **Introduction to HowNet**. *Zhendong Dong and Qiang Dong*. [[pdf (Chinese)](./resources/2003_知网.pdf)]
 > This paper gives an overall introduction to HowNet, including its features, philosophy and constructing method.

2. **HowNet - a hybrid language and knowledge resource**. *Zhendong Dong and Qiang Dong*. NLP-KE 2003. [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=1276017)]
 > This paper gives a brief introduction to HowNet.

3. **KDML — Knowledge Database Mark-up Language**. *Zhendong Dong and Qiang Dong*. [[pdf (Chinese)](./resources/2003_KDML-知网知识系统描述语言.pdf)]
 > This paper gives a detailed introduction to Knowledge Database Mark-up Language, the mark-up language used in HowNet.

4. **Sememe knowledge computation: a review of recent advances in application and expansion of sememe knowledge bases**. *Fanchao Qi, Ruobing Xie, Yuan Zang, Zhiyuan Liu, Maosong Sun*. Frontiers of Computer Science 2021. [[pdf](https://academic.hep.com.cn/fcs/CN/article/downloadArticleFile.do?attachType=PDF&id=27793&1632051791615)]
 > This paper summarizes the recent advances in application and expansion of sememe knowledge bases.

### Applications of Sememes
1. **Turn the Combination Lock: Learnable Textual Backdoor Attacks via Word Substitution**. *Fanchao Qi, Yuan Yao, Sophia Xu, Zhiyuan Liu, Maosong Sun*. ACL-IJCNLP 2021. [[pdf](https://aclanthology.org/2021.acl-long.377.pdf)] [[code](https://github.com/thunlp/BkdAtk-LWS)]
1. **LET: Linguistic Knowledge Enhanced Graph Transformer for Chinese Short Text Matching**. *Boer Lyu, Lu Chen, Su Zhu, Kai Yu*. AAAI-21. [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/17592/17399)] [[code](https://github.com/lbe0613/LET)]
1. **Conceptualized and Contextualized Gaussian Embedding**. *Chen Qian, Fuli Feng, Lijie Wen, Tat-Seng Chua*. AAAI-21. [[pdf](https://www.aaai.org/AAAI21Papers/AAAI-3949.QianC.pdf)] 
1. **Chinese Lexical Simplification**. *Jipeng Qiang, Xinyu Lu, Yun Li, Yunhao Yuan, Xindong Wu*. TASLP 2021. [[pdf](https://ieeexplore.ieee.org/document/9439908)] [[code](https://github.com/luxinyu1/Chinese-LS)]
1. **Word-level Textual Adversarial Attacking as Combinatorial Optimization**. *Yuan Zang, Fanchao Qi, Chenghao Yang, Zhiyuan Liu, Meng Zhang, Qun Liu, Maosong Sun*. ACL 2020. [[pdf](https://arxiv.org/pdf/1910.12196.pdf)] [[code](https://github.com/thunlp/SememePSO-Attack)]
1. **Try to Substitute: An Unsupervised Chinese Word Sense Disambiguation Method Based on HowNet**. *Bairu Hou, Fanchao Qi, Yuan Zang, Xurui Zhang, Zhiyuan Liu, Maosong Sun*. COLING 2020. [[pdf](https://www.aclweb.org/anthology/2020.coling-main.155.pdf)] [[code](https://github.com/thunlp/SememeWSD)]
1. **End to End Chinese Lexical Fusion Recognition with Sememe Knowledge**. *Yijiang Liu, Meishan Zhang, Donghong Ji*. COLING 2020. [[pdf](https://aclanthology.org/2020.coling-main.263.pdf)] [[code](https://github.com/liuyijiang1994/chinese_lexical_fusion)]
1. **AliMe KG: Domain Knowledge Graph Construction andApplication in E-commerce**. *Feng-Lin Li, Hehong Chen, Guohai Xu, Tian Qiu, Feng Ji, Ji Zhang, Haiqing Chen*. CIKM 2020. [[pdf](https://dl.acm.org/doi/pdf/10.1145/3340531.3412685)]
1. **Improving Sequence Modeling Ability of Recurrent Neural Networks via Sememes**. *Yujia Qin, Fanchao Qi, Sicong Ouyang, Zhiyuan Liu, Cheng Yang, Yasheng Wang, Qun Liu, Maosong Sun*. TASLP 2020. [[pdf](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9149672)] [[code](https://github.com/thunlp/SememeRNN)]
1. **Incorporating Sememes into Chinese Definition Modeling**. *Liner Yang, Cunliang Kong, Yun Chen, Yang Liu, Qinan Fan, Erhong Yang*. TASLP 2020. [[pdf](https://ieeexplore.ieee.org/document/9072279/)] [[code](https://github.com/blcuicall/AutoDict)]
1. **Enhancing Transformer with Sememe Knowledge**. *Yuhui Zhang, Chenghao Yang, Zhengping Zhou, Zhiyuan Liu*. Rep4NLP 2020. [[pdf](https://www.aclweb.org/anthology/2020.repl4nlp-1.21.pdf)]
1. **Multi-channel Reverse Dictionary Model**. *Lei Zhang, Fanchao Qi, Zhiyuan Liu, Yasheng, Wang, Qun Liu, Maosong Sun*. AAAI-20. [[pdf](https://arxiv.org/pdf/1912.08441.pdf)] [[code](https://github.com/thunlp/MultiRD)]
1. **K-BERT: Enabling Language Representation with Knowledge Graph**. *Weijie Liu, Peng Zhou, Zhe Zhao, Zhiruo Wang, Qi Ju, Haotang Deng and Ping Wang*. AAAI-20. [[pdf](https://ojs.aaai.org/index.php/AAAI/article/view/5681/5537)] [[code](https://github.com/autoliuweijie/K-BERT)]
1. **Leveraging Human Prior Knowledge to Learn Sense Representations**. *Tong Zhang, Wei Ye, Xiangyu Xi, Longyin Zhang, Shikun Zhang, Wen Zhao*. ECAI 2020. [[pdf](http://ecai2020.eu/papers/603_paper.pdf)]
1. **Lexical and Compositional Stream Learning for Event Detection with Sememe Knowledge**. *Jiale Yuan, Xin Xin, Ping Guo*. ICIST 2020. [[pdf](https://ieeexplore.ieee.org/abstract/document/9202312)]
1. **Modeling Semantic Compositionality with Sememe Knowledge**. *Fanchao Qi, Junjie Huang, Chenghao Yang, Zhiyuan Liu, Xiao Chen, Qun Liu and Maosong Sun*. ACL 2019. [[pdf](https://www.aclweb.org/anthology/P19-1571)] [[code](https://github.com/thunlp/Sememe-SC)]
1. **Chinese Relation Extraction with Multi-Grained Information and External Linguistic Knowledge**. *Ziran Li, Ning Ding, Zhiyuan Liu, Haitao Zheng and Ying Shen*. ACL 2019. [[pdf](https://www.aclweb.org/anthology/P19-1430)] [[code](https://github.com/thunlp/Chinese_NRE)]
1. **Unsupervised Neural Aspect Extraction with Sememes**. *Ling Luo, Xiang Ao, Yan Song, Jinyao Li, Xiaopeng Yang, Qing He and Dong Yu*. IJCAI 2019. [[pdf](https://www.ijcai.org/proceedings/2019/0712.pdf)]
1. **Semantic Hilbert Space for Text Representation Learning**. *Benyou Wang, Qiuchi Li, Massimo Melucci, Dawei Song*. WWW 2019. [[pdf](https://dl.acm.org/doi/pdf/10.1145/3308558.3313516)] [[code](https://github.com/wabyking/qnn)]
1. **Semantic Representation Learning Based on HowNet**. *Jingwen Zhu, Yuji Yang, Bin Xu and Juanzi Li*. JCIP 2019. [[pdf (Chinese)](http://jcip.cipsc.org.cn/CN/abstract/abstract2729.shtml#)]
1. **A Word Representation Method Based on HowNet**. *Yang Chen and Zhiyong Luo*. Acta Scientiarum Naturalium Universitatis Pekinensis 2019. [[pdf (Chinese)](http://xbna.pku.edu.cn/CN/abstract/abstract3297.shtml#1)]
1. **Evaluating Semantic Rationality of a Sentence: A Sememe-Word-Matching Neural Network based on HowNet**. *Shu Liu, Jingjing Xu and Xuancheng Ren*. NLPCC 2019. [[pdf](http://tcci.ccf.org.cn/conference/2019/papers/250.pdf)]
1. **Language Modeling with Sparse Product of Sememe Experts**. *Yihong Gu, Jun Yan, Hao Zhu, Zhiyuan Liu, Ruobing Xie, Maosong Sun, Fen Lin and Leyu Lin*. EMNLP 2018. [[pdf](http://aclweb.org/anthology/D18-1493)] [[code](https://github.com/thunlp/SDLM-pytorch)]
1. **Chinese LIWC Lexicon Expansion via Hierarchical Classification of Word Embeddings with Sememe Attention**. *Xiangkai Zeng, Cheng Yang, Cunchao Tu, Zhiyuan Liu and Maosong Sun*. AAAI-18. [[pdf](http://nlp.csai.tsinghua.edu.cn/~lzy/publications/aaai2018_cliwc.pdf)] [[code](https://github.com/thunlp/Auto_CLIWC)]
1. **Improved Word Representation Learning with Sememes**. *Yilin Niu, Ruobing Xie, Zhiyuan Liu and Maosong Sun*. ACL 2017. [[pdf](http://www.aclweb.org/anthology/P17-1187)] [[code](https://github.com/thunlp/SE-WRL)]
1. **Embedding for Words and Word Senses Based on Human Annotated
   Knowledge Base: A Case Study on HowNet**. *Maosong Sun and Xinxiong Chen*. JCIP 2016. [[pdf (Chinese)](http://jcip.cipsc.org.cn/CN/article/downloadArticleFile.do?attachType=PDF&id=2293)]
1. **Multi-aspect sentiment analysis for Chinese online social reviews based on topic modeling and HowNet lexicon**. *Xianghua Fu, Guo Li, Yanyan Guo and Zhiqiang Wang*. Knowledge-Based Systems 2013. [[pdf](https://www.sciencedirect.com/science/article/pii/S0950705112002158)]
1. **Employing Morphological Structures and Sememes for Chinese Event Extraction**. *Peifeng Li and Guodong Zhou*. COLING 2012. [[pdf](https://www.aclweb.org/anthology/C12-1099)]
1. **Method of discriminant for Chinese sentence sentiment orientation based on HowNet**. *Lei Dang and Lei Zhang*. Application Research of Computers 2010. [[pdf (Chinese)](http://www.arocmag.com/getarticle/?aid=0566ec39f836c6d3)]
1. **HowNet Based Chinese Question Automatic Classification**. *Jingguang Sun, Dongfeng Cai, Dexin Lv, and Yanju Dong*. JCIP 2007. [[pdf (Chinese)](http://jcip.cipsc.org.cn/CN/article/downloadArticleFile.do?attachType=PDF&id=703)]
1. **Word Sense Disambiguation through Sememe Labeling**. *Xiangyu Duan, Jun Zhao and Bo Xu*. IJCAI 2007. [[pdf](https://www.aaai.org/Papers/IJCAI/2007/IJCAI07-257.pdf)]
1. **Analogy Generation with HowNet**. *Tony Veale*. IJCAI 2005. [[pdf](https://www.ijcai.org/Proceedings/05/Papers/0620.pdf)]
1. **Semantic orientation computing based on HowNet**. *Yanlan Zhu, Jin Min, Yaqian Zhou, Xuanjing Huang and Lide Wu*. JCIP 2005. [[pdf (Chinese)](http://jcip.cipsc.org.cn/UserFiles/File/678%E5%9F%BA%E4%BA%8EHowNet%E7%9A%84%E8%AF%8D%E6%B1%87%E8%AF%AD%E4%B9%89%E5%80%BE%E5%90%91%E8%AE%A1%E7%AE%97_%E6%9C%B1%E5%AB%A3%E5%B2%9A.pdf)]
1. **Chinese word sense disambiguation using HowNet**. *Yuntao Zhang, Ling Gong and Yongcheng Wang*. ICNC 2005. [[pdf](https://link.springer.com/content/pdf/10.1007%2F11539087_123.pdf)]
1. **Word Similarity Computing Based on HowNet**. *Qun Liu and Sujian Li*. International Journal of Computational Linguistics & Chinese Language Processing 2002. [[pdf (Chinese)](http://sewm.pku.edu.cn/QA/reference/hownet/WordSimilarity/%A1%B6%BB%F9%D3%DA%A3%BC%D6%AA%CD%F8%A3%BE%B5%C4%B4%CA%BB%E3%D3%EF%D2%E5%CF%E0%CB%C6%B6%C8%BC%C6%CB%E3%A1%B7%C2%DB%CE%C4.pdf)]

### Expansion of Sememe Knowledge Bases

1. **Automatic Construction of Sememe Knowledge Bases via Dictionaries**. *Fanchao Qi, Yanyi Chen, Fengyu Wang, Zhiyuan Liu, Maosong Sun*. Findings of ACL: ACL-IJCNLP 2021. [[pdf](https://arxiv.org/pdf/2105.12400)] [[code](https://github.com/thunlp/DictSKB)]
1. **Towards Building a Multilingual Sememe Knowledge Base: Predicting Sememes for BabelNet Synsets**. *Fanchao Qi, Liang Chang, Maosong Sun, Sicong Ouyang and Zhiyuan Liu*. AAAI-20. [[pdf](https://arxiv.org/pdf/1912.01795.pdf)] [[code](https://github.com/thunlp/BabelNet-Sememe-Prediction)]
1. **Sememe Tree Prediction for English-Chinese Word Pairs**. *Baoju Liu, Xuejun Shang, Liqing Liu, Yuanpeng Tan, Lei Hou, Juanzi Li*. CCKS 2020. [[pdf](https://link.springer.com/content/pdf/10.1007%2F978-981-16-1964-9_2.pdf)]
1. **Incorporating synonym for lexical sememe prediction: An attention-based model**. *Xiaojun Kang, Bing Li, Hong Yao, Qingzhong Liang, Shengwen Li, Junfang Gong, Xinchuan Li*. Applied Sciences 2020. [[pdf](https://www.mdpi.com/2076-3417/10/17/5996/pdf)]
1. **Lexical Sememe Prediction using Dictionary Definitions by Capturing Local Semantic Correspondence**. *Jiaju Du, Fanchao Qi, Maosong Sun and Zhiyuan Liu*. arXiv 2020. [[pdf](https://arxiv.org/pdf/2001.05954)]
1. **OpenHowNet: An Open Sememe-based Lexical Knowledge Base**. Fanchao Qi, Chenghao Yang, Zhiyuan Liu, Qiang Dong, Maosong Sun, Zhendong Dong. arXiv 2019. [[pdf](https://arxiv.org/pdf/1901.09957.pdf)] [[code](https://github.com/thunlp/OpenHowNet)]
1. **Cross-lingual Lexical Sememe Prediction**. *Fanchao Qi, Yankai Lin, Maosong Sun, Hao Zhu, Ruobing Xie and Zhiyuan Liu*. EMNLP 2018. [[pdf](http://aclweb.org/anthology/D18-1033)] [[code](https://github.com/thunlp/CL-SP)]
1. **Lexical Sememe Prediction with RNN and Modern Chinese Dictionary**. *Mei Bai, Pin lv, Xu Long*. ICNC-FSKD 2018. [[pdf](https://ieeexplore.ieee.org/stampPDF/getPDF.jsp?tp=&arnumber=8687260&ref=)]
1. **Sememe Prediction: Learning Semantic Knowledge from Unstructured Textual Wiki Descriptions**. *Wei Li, Xuancheng Ren, Damai Dai, Yunfang Wu, Houfeng Wang and Xu Sun*. arXiv 2018. [[pdf](https://arxiv.org/pdf/1808.05437)] [[code](https://github.com/lancopku/Sememe_prediction)]
1. **Extended HowNet 2.0: An Entity-Relation Common-Sense Representation Model**. *Wei-Yun Ma and Yueh-Yin Shih*. LREC 2018. [[pdf](http://www.lrec-conf.org/proceedings/lrec2018/pdf/547.pdf)]
1. **Incorporating Chinese Characters of Words for Lexical Sememe Prediction**. *Huiming Jin, Hao Zhu, Zhiyuan Liu, Ruobing Xie, Maosong Sun, Fen Lin and Leyu Lin*. ACL 2018. [[pdf](https://www.aclweb.org/anthology/P18-1227.pdf)] [[code](https://github.com/thunlp/Character-enhanced-Sememe-Prediction)]
1. **Lexical Sememe Prediction via Word Embeddings and Matrix Factorization**. *Ruobing Xie, Xingchi Yuan, Zhiyuan Liu and Maosong Sun*. IJCAI 2017. [[pdf](https://www.ijcai.org/proceedings/2017/0587.pdf)] [[code](https://github.com/thunlp/Sememe_prediction)]
1. **E-HowNet and Automatic Construction of a Lexical Ontology**. *Wei-Te Chen, Su-Chu Lin, Shu-Ling Huang, You-Shan Chung and Keh-Jiann Chen*. COLING 2010. [[pdf](https://aclanthology.info/pdf/C/C10/C10-3012.pdf)]
1. **Extended-HowNet: A Representational Framework for Concepts**. *Keh-Jiann Chen, Shu-Ling Huang, Yueh-Yin Shih and Yi-Jun Chen*. OntoLex 2005. [[pdf](http://www.aclweb.org/anthology/I05-7001)]

