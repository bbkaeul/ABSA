# Datasets
- **[SemEval 2014]** SemEval-2014 Task 4: Aspect Based Sentiment Analysis [data](https://github.com/jiangqn/aspect_extraction/tree/master/data/official_data/SemEval-2014)
- **[SemEval-2016 Task 5]** SemEval-2016 Task 5: Aspect Based Sentiment Analysis [data](https://alt.qcri.org/semeval2016/task5/index.php?id=data-and-tools)
- **[Adversarial Test Set for SemEval-14]** Tasty Burgers, Soggy Fries: Probing Aspect Robustness in Aspect-Based Sentiment Analysis @EMNLP 2020 [data](https://github.com/zhijing-jin/ARTS_TestSet)
- **[MAMS]** A Challenge Dataset and Effective Models for Aspect-Based Sentiment Analysis @EMNLP 2019 [paper](https://aclanthology.org/D19-1654.pdf) [data](https://github.com/siat-nlp/MAMS-for-ABSA)
- **[Twitter]** Adaptive Recursive Neural Network for Target-dependent Twitter Sentiment Classification @ACL 2014 [paper](https://aclanthology.org/P14-2009.pdf) [data](https://github.com/songyouwei/ABSA-PyTorch/tree/master/datasets/acl-14-short-data)
- **[SentiHood]** Sentihood: Targeted aspect based sentiment analysis dataset for urban neighbourhoods @COLING 2016 [paper](https://aclanthology.org/C16-1146/) [data](https://github.com/uclnlp/jack/tree/master/data/sentihood)
- **[TOWE]** Target-oriented Opinion Words Extraction with Target-fused Neural Sequence Labeling @NAACL 2019 [data](https://github.com/NJUNLP/TOWE)
- **[Amazon reviews]** The data span a period of 18 years, including ~35 million reviews up to March 2013. Reviews include product and user information, ratings, and a plaintext review [data](https://snap.stanford.edu/data/web-Amazon.html)
- **[Amazon product data]** This dataset contains product reviews and metadata from Amazon, including 142.8 million reviews spanning May 1996 - July 2014. This dataset includes reviews (ratings, text, helpfulness votes), product metadata (descriptions, category information, price, brand, and image features), and links (also viewed/also bought graphs). [data](http://jmcauley.ucsd.edu/data/amazon/)


# ABSA (Aspect-Based Sentiment Analysis) Paper list
### Survey
Issues and Challenges of Aspect-based Sentiment Analysis: A ComprehensiveSurvey [paper](https://ieeexplore.ieee.org/abstract/document/8976252)
Aspect and Entity Extraction for Opinion Mining [paper](https://www.cs.uic.edu/~lzhang3/paper/ZhangLiu-AEEE.pdf)


### Domain Adaptation (Transfer learning, SNE)
Unified Feature and Instance Based Domain Adaptation for Aspect-Based Sentiment Analysis [paper](https://aclanthology.org/2020.emnlp-main.572.pdf)
- Feature-based methods learn a domain-invariant representation with autiliary tasks or domain adversarial learning
- Instance-based methods is to re-weight source instances in order to assign higher weights to instances similar to the target domain and lower weights to instances different from the target domain


### Context-aware classification
Context-Guided BERT for Targeted Aspect-Based Sentiment Analysis [paper](https://arxiv.org/pdf/2010.07523.pdf) [code](https://github.com/frankaging/Quasi-Attention-ABSA)
- Context-Aware Self-Attention Networks [paper](https://arxiv.org/pdf/1902.05766.pdf)
- Compositional De-Attention Networks [paper](https://papers.nips.cc/paper/2019/file/16fc18d787294ad5171100e33d05d4e2-Paper.pdf)

Exploiting BERT for End-to-End Aspect-based Sentiment Analysis @EMNLP 2019 [paper](https://arxiv.org/pdf/1910.00883.pdf) [code](https://github.com/lixin4ever/BERT-E2E-ABSA)

A Unified Generative Framework for Aspect-Based Sentiment Analysis  @ACL 2021 [paper](https://arxiv.org/pdf/2106.04300.pdf) [code](https://github.com/yhcc/BARTABSA)

Attention-based LSTM for Aspect-level Sentiment Classification [paper](https://ieeexplore.ieee.org/abstract/document/8976252)


### Syntax
Does syntax matter? A strong baseline for Aspect-based Sentiment Analysis with RoBERTa @NAACL 2021 [paper](https://arxiv.org/abs/2104.04986) [code](https://github.com/ROGERDJQ/RoBERTaABSA)


### Opinion extraction
Open-Domain Targeted Sentiment Analysis via Span-Based Extraction and Classification @ACL 2019 [paper](https://aclanthology.org/P19-1051.pdf) [code](https://github.com/huminghao16/SpanABSA)

### Aspect Sentiment Triplet Extraction (ASTE)
Bidirectional Machine Reading Comprehension for Aspect Sentiment Triplet Extraction @AAAI 2021 [paper](https://arxiv.org/abs/2103.07665) [code](https://github.com/NKU-IIPLab/BMRC)

###  Pair-wise Aspect and Opinion Terms Extraction (PAOTE)
SpanMlt: A Span-based Multi-Task Learning Framework for Pair-wise Aspect and Opinion Terms Extraction [paper](https://aclanthology.org/2020.acl-main.296.pdf)
