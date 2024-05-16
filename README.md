# awesome-keyphrase-papers
Papers about keyphrase generation and extraction

[Di Wu](https://xiaowu0162.github.io/) and [Kai-Wei Chang](http://web.cs.ucla.edu/~kwchang/)

## Background
Keyphrases are the phrases that identify the most salient concepts in a document. Keyphrase extraction and keyphrase generation are fundamental tasks connected with numerous NLP and IR applications. In this repo, we summarize influential keyphrase-related papers and resources. Papers are selected from \*ACL, EMNLP, AAAI, SIGIR, and other related conferences. **If you have any suggestions or would like to add some papers, please submit an issue or a pull request. Your contribution is much appreciated!** [KeyphraseExtractionSurvey](https://github.com/MySong7NLPer/KeyphraseExtractionSurvey) and [Awesome-Keyphrase-Prediction](https://github.com/HqWu-HITCS/Awesome-Keyphrase-Prediction) are two other great repositories. Also check them out if you are interested.

## Contents
- [Background](#background)
- [Paper List](#paper-list)
  - [Keyphrase Generation](#keyphrase-generation-methods)
  - [Keyphrase Extraction](#keyphrase-extraction-methods)
  - [Evaluation/Empirical Studies/Position](#evaluationempirical-studiesposition)
  - [Surveys](#surveys)
  - [Applications](#applications)
  - [Data/Resource](#dataresources)
  - [Tools](#tools)
- [Conference/Workshop/Tutorials](#conferenceworkshoptutorials)

### Paper List

#### Keyphrase Generation Methods
1. [Deep Keyphrase Generation](https://aclanthology.org/P17-1054/) (Meng et al., ACL 2017)
1. [Keyphrase Generation with Correlation Constraints](https://aclanthology.org/D18-1439/) (Chen et al., EMNLP 2018)
1. [Semi-Supervised Learning for Neural Keyphrase Generation](https://aclanthology.org/D18-1447/) (Ye & Wang, EMNLP 2018)
1. [Title-Guided Encoding for Keyphrase Generation](https://ojs.aaai.org/index.php/AAAI/article/view/4587) (Chen et al., AAAI 2019)
1. [An Integrated Approach for Keyphrase Generation via Exploring the Power of Retrieval and Extraction](https://aclanthology.org/N19-1292/) (Chen et al., NAACL 2019)
1. [Incorporating Linguistic Constraints into Keyphrase Generation](https://aclanthology.org/P19-1515/) (Zhao & Zhang, ACL 2019)
1. [Topic-Aware Neural Keyphrase Generation for Social Media Language](https://aclanthology.org/P19-1240/) (Wang et al., ACL 2019)
1. [Neural Keyphrase Generation via Reinforcement Learning with Adaptive Rewards](https://aclanthology.org/P19-1208/) (Chan et al., ACL 2019)
1. [Diverse Keyphrase Generation with Neural Unlikelihood Training](https://aclanthology.org/2020.coling-main.462/) (Bahuleyan & El Asri, COLING 2020)
1. [One Size Does Not Fit All: Generating and Evaluating Variable Number of Keyphrases](https://aclanthology.org/2020.acl-main.710/) (Yuan et al., ACL 2020)
1. [Exclusive Hierarchical Decoding for Deep Keyphrase Generation](https://aclanthology.org/2020.acl-main.103/) (Chen et al., ACL 2020)
1. [A Preliminary Exploration of GANs for Keyphrase Generation](https://aclanthology.org/2020.emnlp-main.645/) (Swaminathan et al., EMNLP 2020)、
1. [Keyphrase Generation with GANs in Low-Resources Scenarios](https://aclanthology.org/2020.sustainlp-1.12/) (Lancioni et al., sustainlp 2020)
1. [SGG: Learning to Select, Guide, and Generate for Keyphrase Generation](https://aclanthology.org/2021.naacl-main.455/) (Zhao et al., NAACL 2021)
1. [UniKeyphrase: A Unified Extraction and Generation Framework for Keyphrase Prediction](https://aclanthology.org/2021.findings-acl.73/) (Wu et al., Findings 2021)
1. [One2Set: Generating Diverse Keyphrases as a Set](https://aclanthology.org/2021.acl-long.354/) (Ye et al., ACL-IJCNLP 2021)
1. [Select, Extract and Generate: Neural Keyphrase Generation with Layer-wise Coverage Attention](https://aclanthology.org/2021.acl-long.111/) (Ahmad et al., ACL-IJCNLP 2021)
1. [Keyphrase Generation with Fine-Grained Evaluation-Guided Reinforcement Learning](https://aclanthology.org/2021.findings-emnlp.45/) (Luo et al., Findings 2021)
1. [Heterogeneous Graph Neural Networks for Keyphrase Generation](https://aclanthology.org/2021.emnlp-main.213/) (Ye et al., EMNLP 2021)
1. [Structure-Augmented Keyphrase Generation](https://aclanthology.org/2021.emnlp-main.209/) (Kim et al., EMNLP 2021)
1. [HTKG: Deep Keyphrase Generation with Neural Hierarchical Topic Guidance](https://dl.acm.org/doi/abs/10.1145/3477495.3531990) (Zhang et al., SIGIR 2022)
1. [Fast and Constrained Absent Keyphrase Generation by Prompt-Based Learning](https://ojs.aaai.org/index.php/AAAI/article/view/21402) (Wu et al., AAAI 2022)
1. [Unsupervised Deep Keyphrase Generation](https://ojs.aaai.org/index.php/AAAI/article/view/21381) (Shen et al., AAAI 2022)
1. [Automatic Keyphrase Generation by Incorporating Dual Copy Mechanisms in Sequence-to-Sequence Learning](https://aclanthology.org/2022.coling-1.204/) (Wang et al., COLING 2022)
1. [Retrieval-Augmented Multilingual Keyphrase Generation with Retriever-Generator Iterative Training](https://aclanthology.org/2022.findings-naacl.92/) (Gao et al., Findings 2022)
1. [Learning Rich Representation of Keyphrases from Text](https://aclanthology.org/2022.findings-naacl.67/) (Kulkarni et al., Findings 2022)
1. [WR-One2Set: Towards Well-Calibrated Keyphrase Generation](https://aclanthology.org/2022.emnlp-main.491/) (Xie et al., EMNLP 2022)
1. [Keyphrase Generation via Soft and Hard Semantic Corrections](https://aclanthology.org/2022.emnlp-main.529/) (Zhao et al., EMNLP 2022)
1. [Representation Learning for Resource-Constrained Keyphrase Generation](https://aclanthology.org/2022.findings-emnlp.49/) (Wu et al., Findings 2022)
1. [KPDROP: Improving Absent Keyphrase Generation](https://aclanthology.org/2022.findings-emnlp.357/) (Ray Chowdhury et al., Findings 2022)
1. [Keyphrase Generation Beyond the Boundaries of Title and Abstract](https://aclanthology.org/2022.findings-emnlp.427/) (Garg et al., Findings 2022)
1. [Unsupervised Open-domain Keyphrase Generation](https://aclanthology.org/2023.acl-long.592/) (Do et al., ACL 2023)
1. [Data Augmentation for Low-Resource Keyphrase Generation](https://aclanthology.org/2023.findings-acl.534/) (Garg et al., Findings 2023)
1. [General-to-Specific Transfer Labeling for Domain Adaptable Keyphrase Generation](https://aclanthology.org/2023.findings-acl.102/) (Meng et al., Findings 2023)
1. [Rethinking Model Selection and Decoding for Keyphrase Generation with Pre-trained Sequence-to-Sequence Models](https://arxiv.org/abs/2310.06374) (Wu et al., EMNLP 2023)
1. [SimCKP: Simple Contrastive Learning of Keyphrase Representations](https://aclanthology.org/2023.findings-emnlp.199/) (Choi et al., Findings 2023)

#### Keyphrase Extraction Methods
1. [A statistical learning approach to automatic indexing of controlled index terms](https://dl.acm.org/doi/10.5555/254604.254610) (Leung and Kan, JASIS 1997)
1. [KEA: Practical Automatic Keyphrase Extraction](https://dl.acm.org/doi/pdf/10.1145/313238.313437) (Witten et al., DL 1999)
1. [A Language Model Approach to Keyphrase Extraction](https://aclanthology.org/W03-1805/) (Tomokiyo & Hurst, MWE 2003)
1. [TextRank: Bringing Order into Text](https://aclanthology.org/W04-3252/) (Mihalcea & Tarau, EMNLP 2004)
1. [CollabRank: Towards a Collaborative Approach to Single-Document Keyphrase Extraction](https://aclanthology.org/C08-1122/) (Wan & Xiao, COLING 2008)
1. [A ranking approach to keyphrase extraction](https://dl.acm.org/doi/10.1145/1571941.1572113) (Jiang et al., SIGIR 2009)
1. [Automatic Keyphrase Extraction via Topic Decomposition](https://aclanthology.org/D10-1036/) (Liu et al., EMNLP 2010)
1. [KP-Miner: Participation in SemEval-2](https://aclanthology.org/S10-1041/) (El-Beltagy & Rafea, SemEval 2010)
1. [TopicRank: Graph-Based Topic Ranking for Keyphrase Extraction](https://aclanthology.org/I13-1062/) (Bougouin et al., IJCNLP 2013)
1. [Diverse Keyword Extraction from Conversations](https://aclanthology.org/P13-2115/) (Habibi & Popescu-Belis, ACL 2013)
1. [Single Document Keyphrase Extraction Using Label Information](https://aclanthology.org/C14-1139/) (Negi, COLING 2014)
1. [Extracting Discriminative Keyphrases with Learned Semantic Hierarchies](https://aclanthology.org/C16-1089/) (Wang et al., COLING 2016)
1. [Keyphrase Annotation with Graph Co-Ranking](https://aclanthology.org/C16-1277/) (Bougouin et al., COLING 2016)
1. [A Graph Degeneracy-based Approach to Keyword Extraction](https://aclanthology.org/D16-1191/) (Tixier et al., EMNLP 2016)
1. [Supervised Keyphrase Extraction as Positive Unlabeled Learning](https://aclanthology.org/D16-1198/) (Sterckx et al., EMNLP 2016)
1. [Keyphrase Extraction Using Deep Recurrent Neural Networks on Twitter](https://aclanthology.org/D16-1080/) (Zhang et al., EMNLP 2016)
1. [Incorporating Expert Knowledge into Keyphrase Extraction]( https://ojs.aaai.org/index.php/AAAI/article/view/10986) (Gollapalli et al., AAAI 2017)
1. [Salience Rank: Efficient Keyphrase Extraction with Topic Modeling](https://aclanthology.org/P17-2084/) (Teneva & Cheng, ACL 2017)
1. [Multi-Task Learning of Keyphrase Boundary Classification](https://aclanthology.org/P17-2054/) (Augenstein & Søgaard, ACL 2017)
1. [PositionRank: An Unsupervised Approach to Keyphrase Extraction from Scholarly Documents](https://aclanthology.org/P17-1102/) (Florescu & Caragea, ACL 2017)
1. [Learning Feature Representations for Keyphrase Extraction](https://ojs.aaai.org/index.php/AAAI/article/view/12144/12003) (Florescu and Jin, AAAI 2018)
1. [Simple Unsupervised Keyphrase Extraction using Sentence Embeddings](https://aclanthology.org/K18-1022/) (Bennani-Smires et al., CoNLL 2018)
1. [Yake! collection-independent automatic keyword extractor](https://link.springer.com/chapter/10.1007/978-3-319-76941-7_80) (Campos et al., ECIR 2018)
1. [Unsupervised Keyphrase Extraction with Multipartite Graphs](https://aclanthology.org/N18-2105/) (Boudin, NAACL 2018)
1. [Key2Vec: Automatic Ranked Keyphrase Extraction from Scientific Articles using Phrase Embeddings](https://aclanthology.org/N18-2100/) (Mahata et al., NAACL 2018)
1. [DivGraphPointer: A Graph Pointer Network for Extracting Diverse Keyphrases](https://arxiv.org/abs/1905.07689) (Zhang et al., SIGIR 2019)
1. [Glocal: Incorporating Global Information in Local Convolution for Keyphrase Extraction](https://aclanthology.org/N19-1182/) (Prasad & Kan, NAACL 2019)
1. [Open Domain Web Keyphrase Extraction Beyond Language Modeling](https://aclanthology.org/D19-1521/) (Xiong et al., EMNLP-IJCNLP 2019)
1. [Using Human Attention to Extract Keyphrase from Microblog Post](https://aclanthology.org/P19-1588/) (Zhang & Zhang, ACL 2019)
1. [SaSAKE: Syntax and Semantics Aware Keyphrase Extraction from Research Papers](https://aclanthology.org/2020.coling-main.469/) (Santosh et al., COLING 2020)
1. [KeyGames: A Game Theoretic Approach to Automatic Keyphrase Extraction](https://aclanthology.org/2020.coling-main.184/) (Saxena et al., COLING 2020)
1. [A Joint Learning Approach based on Self-Distillation for Keyphrase Extraction from Scientific Documents](https://aclanthology.org/2020.coling-main.56/) (Lai et al., COLING 2020)
1. [SIFRank: a new baseline for unsupervised keyphrase extraction based on pre-trained language model.](https://ieeexplore.ieee.org/document/8954611) (Sun et al., IEEE Access 2020)
1. [Web Document Encoding for Structure-Aware Keyphrase Extraction](https://dl.acm.org/doi/10.1145/3404835.3463067) (Kim et al., SIGIR 2021)
1. [Keyphrase Extraction from Scientific Articles via Extractive Summarization](https://aclanthology.org/2021.sdp-1.6/) (Kontoulis et al., sdp 2021)
1. [Word centrality constrained representation for keyphrase extraction](https://aclanthology.org/2021.bionlp-1.17/) (Gero & Ho, BioNLP 2021)
1. [Exploiting Position and Contextual Word Embeddings for Keyphrase Extraction from Scientific Papers](https://aclanthology.org/2021.eacl-main.136/) (Patel & Caragea, EACL 2021)
1. [Keyphrase Extraction with Incomplete Annotated Training Data](https://aclanthology.org/2021.wnut-1.4/) (Lei et al., WNUT 2021)
1. [Importance Estimation from Multiple Perspectives for Keyphrase Extraction](https://aclanthology.org/2021.emnlp-main.215/) (Song et al., EMNLP 2021)
1. [Unsupervised Keyphrase Extraction by Jointly Modeling Local and Global Context](https://aclanthology.org/2021.emnlp-main.14/) (Liang et al., EMNLP 2021)
1. [AttentionRank: Unsupervised Keyphrase Extraction using Self and Cross Attentions](https://aclanthology.org/2021.emnlp-main.146/) (Ding & Luo, EMNLP 2021)
1. [UCPhrase: Unsupervised Context-aware Quality Phrase Tagging](https://dl.acm.org/doi/abs/10.1145/3447548.3467397) (Gu et al., KDD 2021)
1. [AGRank: Augmented Graph-based Unsupervised Keyphrase Extraction](https://aclanthology.org/2022.aacl-main.19/) (Ding & Luo, AACL-IJCNLP 2022)
1. [Hyperbolic Relevance Matching for Neural Keyphrase Extraction](https://aclanthology.org/2022.naacl-main.419/) (Song et al., NAACL 2022)
1. [MDERank: A Masked Document Embedding Rank Approach for Unsupervised Keyphrase Extraction](https://aclanthology.org/2022.findings-acl.34/) (Zhang et al., Findings 2022)
1. [Unsupervised Keyphrase Extraction via Interpretable Neural Networks](https://aclanthology.org/2023.findings-eacl.82/) (Joshi et al., Findings 2023)
1. [PromptRank: Unsupervised Keyphrase Extraction Using Prompt](https://aclanthology.org/2023.acl-long.545/) (Kong et al., ACL 2023)
1. [Improving Embedding-based Unsupervised Keyphrase Extraction by Incorporating Structural Information](https://aclanthology.org/2023.findings-acl.66/) (Song et al., Findings 2023)
1. [Unsupervised Keyphrase Extraction by Learning Neural Keyphrase Set Function](https://aclanthology.org/2023.findings-acl.156/) (Song et al., Findings 2023)
1. [Multi-Task Knowledge Distillation with Embedding Constraints for Scholarly Keyphrase Boundary Classification](https://aclanthology.org/2023.emnlp-main.805) (Park & Caragea, EMNLP 2023)
1. [SAMRank: Unsupervised Keyphrase Extraction using Self-Attention Map in BERT and GPT-2](https://aclanthology.org/2023.emnlp-main.630) (Kang & Shin, EMNLP 2023)
1. [HyperRank: Hyperbolic Ranking Model for Unsupervised Keyphrase Extraction](https://aclanthology.org/2023.emnlp-main.997/) (Song et al., EMNLP 2023)
1. [Mitigating Over-Generation for Unsupervised Keyphrase Extraction with Heterogeneous Centrality Detection](https://aclanthology.org/2023.emnlp-main.1017/) (Song et al., EMNLP 2023)
1. [Clustering-based Sampling for Few-Shot Cross-Domain Keyphrase Extraction](https://aclanthology.org/2024.findings-eacl.82/) (Mishra et al., Findings 2024)

#### Evaluation/Empirical Studies/Position
1. [TermITH-Eval : a French Standard-Based Resource for Keyphrase Extraction Evaluation](https://hal.science/hal-01693805/) (Bougouin, LREC 2016)
1. [Human-competitive tagging using automatic keyphrase extraction](https://aclanthology.org/D09-1137/) (Medelyan et al., EMNLP 2009)
1. [Approximate Matching for Evaluating Keyphrase Extraction](https://aclanthology.org/R09-1086/) (Zesch & Gurevych, RANLP 2009)
1. [Evaluating N-gram based Evaluation Metrics for Automatic Keyphrase Extraction](https://aclanthology.org/C10-1065/) (Kim et al., COLING 2010)
1. [How Document Pre-processing affects Keyphrase Extraction Performance](https://aclanthology.org/W16-3917/) (Boudin et al., WNUT 2016)
1. [Evaluating anaphora and coreference resolution to improve automatic keyphrase extraction](https://aclanthology.org/C16-1077/) (Basaldella et al., COLING 2016)
1. [Creation and evaluation of large keyphrase extraction collections with multiple opinions](https://link.springer.com/article/10.1007/s10579-017-9395-6) (Sterckx et al., Language Resources and Evaluation 2018)
1. [Encoding Conversation Context for Neural Keyphrase Extraction from Microblog Posts](https://aclanthology.org/N18-1151/) (Zhang et al., NAACL 2018)
1. [Keyphrase Generation: A Text Summarization Struggle](https://aclanthology.org/N19-1070/) (Çano & Bojar, NAACL 2019)
1. [Understanding the Tradeoff between Cost and Quality of Expert Annotations for Keyphrase Extraction](https://aclanthology.org/2020.law-1.7/) (Chau et al., LAW 2020)
1. [Large-Scale Evaluation of Keyphrase Extraction Models](https://dl.acm.org/doi/abs/10.1145/3383583.3398517) (Gallina et al., JCDL 2020)
1. [Scientific Keyphrase Identification and Classification by Pre-Trained Language Models Intermediate Task Transfer Learning](https://aclanthology.org/2020.coling-main.472/) (Park & Caragea, COLING 2020)
1. [An Empirical Study on Neural Keyphrase Generation](https://aclanthology.org/2021.naacl-main.396/) (Meng et al., NAACL 2021)
1. [Redefining Absent Keyphrases and their Effect on Retrieval Effectiveness](https://aclanthology.org/2021.naacl-main.330/) (Boudin & Gallina, NAACL 2021)
1. [KPEval: Towards Fine-Grained Semantic-Based Keyphrase Evaluation](https://arxiv.org/abs/2303.15422) (Boudin & Gallina, Findings 2024)

#### Surveys
1. [Automatic Keyphrase Extraction: A Survey of the State of the Art](https://aclanthology.org/P14-1119/) (Hasan & Ng, ACL 2014)
1. [Keyword and Keyphrase Extraction Techniques: A Literature Review](https://www.researchgate.net/publication/272372039_Keyword_and_Keyphrase_Extraction_Techniques_A_Literature_Review) (Siddiqi and Sharan, IJCA 2015)
1. [Keyphrase Generation: A Multi-Aspect Survey](https://ieeexplore.ieee.org/abstract/document/8981519) (Cano and Bojar, IEEE FRUCT 2019)
1. [Automatic keyphrase extraction: a survey and trends](https://link.springer.com/article/10.1007/s10844-019-00558-9) (Merrouni et al., JIIS 2020)
1. [A Survey on Recent Advances in Keyphrase Extraction from Pre-trained Language Models](https://aclanthology.org/2023.findings-eacl.161/) (Song et al., Findings 2023)
1. [From statistical methods to deep learning, automatic keyphrase prediction: A survey](https://www.sciencedirect.com/science/article/pii/S030645732300119X) (Xie et. al., Information Processing & Management 2023)

#### Applications
1. [Automatic phrase indexing for document retrieval](https://dl.acm.org/doi/pdf/10.1145/42005.42016) (Fagan, SIGIR 1987)
1. [A Just-In-Time Keyword Extraction from Meeting Transcripts](https://aclanthology.org/N13-1109/) (Song et al., NAACL 2013)
1. [Keyphrase Extraction for N-best Reranking in Multi-Sentence Compression](https://aclanthology.org/N13-1030/) (Boudin & Morin, NAACL 2013)
1. [Joint Learning of Chinese Words, Terms and Keywords](https://aclanthology.org/D14-1186/) (Cao et al., EMNLP 2014)
1. [Financial Keyword Expansion via Continuous Word Vector Representations](https://aclanthology.org/D14-1152/) (Tsai & Wang, EMNLP 2014)
1. [Citation-Enhanced Keyphrase Extraction from Research Papers: A Supervised Approach](https://aclanthology.org/D14-1150/) (Caragea et al., EMNLP 2014)
1. [Cross-Lingual Information to the Rescue in Keyword Extraction](https://aclanthology.org/P14-5001/) (Huang et al., ACL 2014)
1. [Automatic Keyword Extraction on Twitter](https://aclanthology.org/P15-2105/) (Marujo et al., ACL-IJCNLP 2015)
1. [Extraction of Keywords of Novelties From Patent Claims](https://aclanthology.org/C16-1113/) (Suzuki & Takatsuka, COLING 2016)
1. [Real-Time Keyword Extraction from Conversations](https://aclanthology.org/E17-2074/) (Meladianos et al., EACL 2017)
1. [Keyphrases Extraction from User-Generated Contents in Healthcare Domain Using Long Short-Term Memory Networks](https://aclanthology.org/W18-2304/) (Saputra et al., BioNLP 2018)
1. [Leveraging Just a Few Keywords for Fine-Grained Aspect Detection Through Weakly Supervised Co-Training](https://aclanthology.org/D19-1468/) (Karamanolakis et al., EMNLP-IJCNLP 2019)
1. [A Human-AI Loop Approach for Joint Keyword Discovery and Expectation Estimation in Micropost Event Detection](https://ojs.aaai.org/index.php/AAAI/article/view/5626) (Bhardwaj et al., AAAI 2020)
1. [Understanding Medical Conversations with Scattered Keyword Attention and Weak Supervision from Responses](https://ojs.aaai.org/index.php/AAAI/article/view/6412) (Shi et al., AAAI 2020)
1. [Keywords-Guided Abstractive Sentence Summarization](https://ojs.aaai.org/index.php/AAAI/article/view/6333) (Li et al., AAAI 2020)
1. [Keyphrase Generation for Scientific Document Retrieval](https://aclanthology.org/2020.acl-main.105/) (Boudin et al., ACL 2020)
1. [Diverse, Controllable, and Keyphrase-Aware: A Corpus and Method for News Multi-Headline Generation](https://aclanthology.org/2020.emnlp-main.505/) (Liu et al., EMNLP 2020)
1. [Cross-Media Keyphrase Prediction: A Unified Framework with Multi-Modality Multi-Head Attention and Image Wordings](https://aclanthology.org/2020.emnlp-main.268/) (Wang et al., EMNLP 2020)
1. [Incorporating Multimodal Information in Open-Domain Web Keyphrase Extraction](https://aclanthology.org/2020.emnlp-main.140/) (Wang et al., EMNLP 2020)
1. [Bayesian Critiquing with Keyphrase Activation Vectors for VAE-based Recommender Systems](https://dl.acm.org/doi/abs/10.1145/3404835.3463108) (Yang et al., NAACL 2021)
1. [KPQA: A Metric for Generative Question Answering Using Keyphrase Weights](https://aclanthology.org/2021.naacl-main.170/) (Lee et al., NAACL 2021)
1. [Arabic Keyphrase Extraction: Enhancing Deep Learning Models with Pre-trained Contextual Embedding and External Features](https://aclanthology.org/2022.wanlp-1.30/) (Alharbi & Al-Muhtasab, WANLP 2022)
1. [Towards Better Multi-modal Keyphrase Generation via Visual Entity Enhancement and Multi-granularity Image Noise Filtering](https://arxiv.org/abs/2309.04734) (ACM MM 2023)

#### Data/Resources
1. Please also check out [KeyphraseExtractionSurvey](https://github.com/MySong7NLPer/KeyphraseExtractionSurvey#dataset) for early keyphrase extraction datasets.
1. [KP20k, Inspec, Krapivin, NUS, SemEval](https://aclanthology.org/P17-1054/) (Meng et al., ACL 2017)
1. [KPTimes](https://arxiv.org/abs/1911.12559) (Gallina et al., INLG 2019)
1. [OpenKP](https://www.aclweb.org/anthology/D19-1521/) (Xiong et al., EMNLP 2019)
1. [OAGK](https://www.aclweb.org/anthology/N19-1070/) (Cano et al., NAACL 2019)
1. [StackEx](https://www.aclweb.org/anthology/2020.acl-main.710/) (Yuan et al., ACL 2020)
1. [KPBiomed](https://aclanthology.org/2022.louhi-1.6/) (Houbre et al., Louhi 2022)
1. [Keyphrase Prediction from Video Transcripts: New Dataset and Directions](https://aclanthology.org/2022.coling-1.624/) (Veyseh et al., COLING 2022)
1. [EcommerceMKP](https://aclanthology.org/2022.findings-naacl.92/) (Gao et al., Findings 2022)
1. [AcademicMKP](https://aclanthology.org/2022.findings-naacl.92/) (Gao et al., Findings 2022)
1. [LipKey](https://aclanthology.org/2022.coling-1.303/) (Koto et al., COLING 2022)
1. [LDKP](https://arxiv.org/pdf/2203.15349.pdf/) (Mahata et al., arXiv 2022)
1. [A new dataset for multilingual keyphrase generation](https://openreview.net/pdf?id=47qVX2pa-2) (Piedboeuf and Langlais, NeurIPS 2022 Datasets and Benchmarks track)

#### Tools
1. [DKPro Keyphrases: Flexible and Reusable Keyphrase Extraction Experiments](https://aclanthology.org/P14-5006/) (Erbs et al., ACL 2014)
1. [pke: an open source python-based keyphrase extraction toolkit](https://aclanthology.org/C16-2015/) (Boudin, COLING 2016)
1. [OpenNMT-kpg](https://github.com/memray/OpenNMT-kpg-release)
1. [keyphrase-generation-rl](https://github.com/kenchan0226/keyphrase-generation-rl)
1. [ir_using_kg](https://github.com/boudinfl/ir-using-kg)
1. [multilingual_keyphrase_generation](https://github.com/Yifan-Gao/multilingual_keyphrase_generation)
1. [dlkp](https://github.com/midas-research/dlkp)
1. [DeepKPG](https://github.com/uclanlp/DeepKPG)
1. [KPEval](https://github.com/uclanlp/KPEval)

### Conference/Workshop/Tutorials
- [Automatic Keyphrase Extraction from Text: A Walk-through](https://intelligence-csd-auth-gr.github.io/KE_Tutorial/), ECAI 2020
- [A Tutorial on Keyphrasification](https://keyphrasification.github.io/), ECIR 2022
