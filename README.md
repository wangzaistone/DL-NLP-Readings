# My Reading Lists of Deep Learning and Natural Language Processing

## Table of Contents
1. [Natural Language Processing](#natural-language-processing)
    1. [Machine Translation](#machine-translation)
    2. [Text Classification](#text-classification)
    3. [Dialogue System](#dialogue-system)
    4. [Embeddings](#embeddings)
    5. [Machine/Reading Comprehension, Question Answering, Natural Language Understanding](#machinereading-comprehension-question-answering-natural-language-understanding)
        1. [Memory Network](#memory-network)
    6. [Knowledge Base Representation / Knowledge Representation Learning](#knowledge-base-representation--knowledge-representation-learning)
    7. [Semantic Related](#semantic-related)
        1. [Slides and Introduction](#slides-and-introduction)
        2. [Coreference/Anaphora Resolution](#coreferenceanaphora-resolution)
        3. [Semantic Role Labeling](#semantic-role-labeling)
        4. [Sequence Labeling](#sequence-labeling)
        5. [Dependency Parser](#dependency-parser)
        6. [Punctuation Restoration](#punctuation-restoration)
        7. [Grammatical Error Correction](#grammatical-error-correction)
    8. [Sentiment Analysis / Stance Detection](#sentiment-analysis--stance-detection)
    9. [Multi-Model](#multi-model)
2. [Commonsense](#commonsense)
    1. [Script Knowledge](#script-knowledge)
3. [Deep Learning](#deep-learning)
    1. [Recurrent Neural Networks](#recurrent-neural-networks)
    2. [Optimizations](#optimizations)
    3. [Neural Turing Machines](#neural-turing-machines)
    4. [Capsules](#capsules)
    5. [Generative Adversarial Networks](#generative-adversarial-networks)
    6. [Highway Networks](#highway-networks)
    7. [Convolutional Networks](#convolutional-networks)
    8. [Residual Networks](#residual-networks)
    9. [Multi-Model](#multi-model)
4. [Reinforcement Learning](#reinforcement-learning)

## Natural Language Processing
- **Speech and Language Processing**, [[book]](https://web.stanford.edu/~jurafsky/slp3/).

### Machine Translation
- **A Convolutional Encoder Model for Neural Machine Translation**, [[paper]](https://arxiv.org/abs/1611.02344), sources: [[facebookresearch/fairseq]](https://github.com/facebookresearch/fairseq).
- **Neural Machine Translation by Jointly Learning to Align and Translate**, [[paper]](https://arxiv.org/abs/1409.0473), sources: [[lisa-groundhog/GroundHog]](https://github.com/lisa-groundhog/GroundHog/tree/master/experiments/nmt).
- **On the properties of neural machine Translation Encoder-Decoder Approaches**, [[paper]](https://arxiv.org/abs/1409.1259).
- **Context Models for OOV Word Translation in Low-Resource Language**, [[paper]](https://arxiv.org/abs/1801.08660).

### Text Classification
- **Bag of Tricks for Efficient Text Classification**, [[paper]](https://arxiv.org/abs/1607.01759), sources: [[facebookresearch/fastText]](https://github.com/facebookresearch/fastText).
- **Convolutional Neural Networks for Sentence Classification**, [[paper]](https://arxiv.org/abs/1408.5882), sources: [[yoonkim/CNN_sentence]](https://github.com/yoonkim/CNN_sentence), [[dennybritz/cnn-text-classification-tf]](https://github.com/dennybritz/cnn-text-classification-tf).
- **Hierarchical Attention Networks for Document Classification**, [[paper]](https://www.cs.cmu.edu/%7Ediyiy/docs/naacl16.pdf), sources: [[richliao/textClassifier]](https://github.com/richliao/textClassifier), [[ematvey/hierarchical-attention-networks]](https://github.com/ematvey/hierarchical-attention-networks).
- **Recurrent Convolutional Neural Networks for Text Classification**, [[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9745/9552), sources: [[knok/rcnn-text-classification]](https://github.com/knok/rcnn-text-classification), [[airalcorn2/Recurrent-Convolutional-Neural-Network-Text-Classifier]](https://github.com/airalcorn2/Recurrent-Convolutional-Neural-Network-Text-Classifier).
- **Which Encoding is the Best for Text Classification in Chinese, English, Japanese and Korean**, [[paper]](https://arxiv.org/abs/1708.02657), sources: [[zhangxiangxiao/glyph]](https://github.com/zhangxiangxiao/glyph).

### Dialogue System
- **A Hierarchical Recurrent Encoder-Decoder for Generative Context-Aware Query Suggestion**, [[paper]](https://arxiv.org/abs/1507.02221), sources: [[sordonia/hred-qs]](https://github.com/sordonia/hred-qs).
- **A Survey on Dialogue Systems - Recent Advances and New Frontiers**, [[paper]](https://arxiv.org/abs/1711.01731), sources: [[shawnspace/survey-in-dialog-system]](https://github.com/shawnspace/survey-in-dialog-system).
- **Adversarial Learning for Neural Dialogue Generation**, [[paper]](https://arxiv.org/abs/1701.06547), sources: [[jiweil/Neural-Dialogue-Generation]](https://github.com/jiweil/Neural-Dialogue-Generation), [[liuyuemaicha/Adversarial-Learning-for-Neural-Dialogue-Generation-in-Tensorflow]](https://github.com/liuyuemaicha/Adversarial-Learning-for-Neural-Dialogue-Generation-in-Tensorflow).
- **Attention with Intention for a Neural Network Conversation Model**, [[paper]](https://arxiv.org/abs/1510.08565).
- **Building End-To-End Dialogue Systems Using Generative Hierarchical Neural Network Models**, [[paper]](https://arxiv.org/abs/1507.04808), sources: [[suriyadeepan/augmented_seq2seq]](https://github.com/suriyadeepan/augmented_seq2seq), [[julianser/hed-dlg]](https://github.com/julianser/hed-dlg), [[sordonia/hed-dlg]](https://github.com/sordonia/hed-dlg), [[julianser/hred-latent-piecewise]](https://github.com/julianser/hred-latent-piecewise), [[julianser/hed-dlg-truncated]](https://github.com/julianser/hed-dlg-truncated).
- **Chatbot with common-sense database**, [[paper]](https://www.diva-portal.org/smash/get/diva2:812049/FULLTEXT01.pdf).
- **Multi-view Response Selection for Human-Computer Conversation**, [[paper]](http://www.aclweb.org/anthology/D16-1036).
- **Neural Responding Machine for Short-Text Conversation**, [[paper]](https://arxiv.org/abs/1503.02364).
- **POMDP-based Statistical Spoken Dialogue Systems: a Review**, [[paper]](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/young2013procieee.pdf).
- **Semantically Conditioned LSTM-based Natural Language Generation for Spoken Dialogue Systems**, [[paper]](https://arxiv.org/abs/1508.01745), sources: [[shawnwun/RNNLG]](https://github.com/shawnwun/RNNLG), [[hit-computer/SC-LSTM]](https://github.com/hit-computer/SC-LSTM).
- **Sequence to Sequence Learning with Neural Networks**, [[paper]](https://arxiv.org/abs/1409.3215), sources: [[farizrahman4u/seq2seq]](https://github.com/farizrahman4u/seq2seq), [[ma2rten/seq2seq]](https://github.com/ma2rten/seq2seq), [[JayParks/tf-seq2seq]](https://github.com/JayParks/tf-seq2seq), [[macournoyer/neuralconvo]](https://github.com/macournoyer/neuralconvo).
- **Sequential Matching Network: A New Architecture for Multi-turn Response Selection in Retrieval-Based Chatbots**, [[paper]](https://arxiv.org/abs/1612.01627), sources: [[MarkWuNLP/MultiTurnResponseSelection]](https://github.com/MarkWuNLP/MultiTurnResponseSelection), [[krayush07/sequential-match-network]](https://github.com/krayush07/sequential-match-network).
- **Deep Reinforcement Learning for Dialogue Generation**, [[paper]](https://arxiv.org/abs/1606.01541), sources: [[liuyuemaicha/Deep-Reinforcement-Learning-for-Dialogue-Generation-in-tensorflow]](https://github.com/liuyuemaicha/Deep-Reinforcement-Learning-for-Dialogue-Generation-in-tensorflow).
- **On-line Active Reward Learning for Policy Optimisation in Spoken Dialogue Systems**, [[paper]](https://arxiv.org/abs/1605.07669).

### Embeddings
- **How to Generate a Good Word Embedding?**, [[paper]](https://arxiv.org/abs/1507.05523), [[blog]](http://licstar.net/archives/620), sources: [[licstar/compare]](https://github.com/licstar/compare).
- **Word and Document Embeddings based on Neural Network Approaches (基于神经网络的词和文档语义向量表示方法研究)**, [[Ph.D. Thesis]](https://arxiv.org/pdf/1611.05962.pdf), [[blog]](http://licstar.net/archives/687).
- **GloVe: Global Vectors for Word Representation**, [[paper]](https://nlp.stanford.edu/pubs/glove.pdf), [[homepage]](https://nlp.stanford.edu/projects/glove/), sources: [[stanfordnlp/GloVe]](https://github.com/stanfordnlp/GloVe).
- **A Neural Probabilistic Language Model**, [[paper]](http://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf).
- **A Simple But Tough-to-beat Baseline for Sentence Embeddings**, [[paper]](https://openreview.net/pdf?id=SyK00v5xx), sources: [[PrincetonML/SIF]](https://github.com/PrincetonML/SIF).
- **A Simple Word Embedding Model for Lexical Substitution**, [[paper]](http://www.aclweb.org/anthology/W15-1501), sources: [[orenmel/lexsub]](https://github.com/orenmel/lexsub).
- **An Ensemble Method to Produce High-Quality Word Embeddings**, [[paper]](https://arxiv.org/abs/1604.01692), [[blog]](https://blog.conceptnet.io/tag/word2vec/), sources: [[commonsense/conceptnet-numberbatch]](https://github.com/commonsense/conceptnet-numberbatch).
- **Dependency-Based Word Embeddings**, [[paper]](http://www.aclweb.org/anthology/P14-2050), [[homepage]](https://levyomer.wordpress.com/2014/04/25/dependency-based-word-embeddings/), [[my blog]](https://isaacchanghau.github.io/2017/05/18/word2vecf/), sources: [[Yoav Goldberg/word2vecf]](https://bitbucket.org/yoavgo/word2vecf), [[IsaacChanghau/Word2VecfJava]](https://github.com/IsaacChanghau/Word2VecfJava/tree/master/src/main/java/com/isaac/word2vecf).
- **context2vec: Learning Generic Context Embedding with Bidirectional LSTM**, [[paper]](http://www.aclweb.org/anthology/K16-1006), sources: [[orenmel/context2vec]](https://github.com/orenmel/context2vec).
- **Enriching Word Vectors with Subword Information**, [[paper]](https://arxiv.org/abs/1607.04606), sources: [[facebookresearch/fastText]](https://github.com/facebookresearch/fastText), [[salestock/fastText.py]](https://github.com/salestock/fastText.py).
- **Exploring the Limits of Language Modeling**, [[paper]](https://arxiv.org/abs/1602.02410), [[slides]](https://www.cs.toronto.edu/~duvenaud/courses/csc2541/slides/lipnet.pdf), sources: [[tensorflow/models/lm_1b]](https://github.com/tensorflow/models/tree/master/research/lm_1b).
- **Recurrent neural network based language model**, [[paper]](http://www.fit.vutbr.cz/research/groups/speech/publi/2010/mikolov_interspeech2010_IS100722.pdf), sources: [[mspandit/rnnlm]](https://github.com/mspandit/rnnlm).
- **HLBL: A Scalable Hierarchical Distributed Language Model**, [[paper]](http://www.cs.toronto.edu/~fritz/absps/andriytree.pdf).
- **Extensions of recurrent neural network language model**, [[paper1]](https://github.com/yihui-he/Natural-Language-Process/blob/master/Extensions%20of%20recurrent%20neural%20network%20language%20model.pdf), [[paper2]](https://www.researchgate.net/publication/224246503_Extensions_of_recurrent_neural_network_language_model), [[slides]](https://pdfs.semanticscholar.org/4162/ce8bbb2fc2f0a059157f9a5b4521d6eb2af5.pdf).
- **Improving Distributional Similarity with Lessons Learned from Word Embeddings**, [[paper]](http://www.aclweb.org/anthology/Q15-1016), [[homepage]](https://levyomer.wordpress.com/2015/03/30/improving-distributional-similarity-with-lessons-learned-from-word-embeddings/), sources: [[Omer Levy/hyperwords]](https://bitbucket.org/omerlevy/hyperwords).
- **Distributed Representations of Words and Phrases and their Compositionality**, [[paper]](https://arxiv.org/abs/1310.4546), [[blog1]](https://www.cnblogs.com/peghoty/p/3857839.html), [[blog2]](http://blog.csdn.net/itplus/article/details/37969519), sources: [[word2vec]](https://code.google.com/archive/p/word2vec/), [[dav/word2vec]](https://github.com/dav/word2vec), [[yandex/faster-rnnlm]](https://github.com/yandex/faster-rnnlm), [[tensorflow/tensorflow/examples/tutorials/word2vec]](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/examples/tutorials/word2vec).
- **Distributed Representations of Sentences and Documents**, [[paper]](https://arxiv.org/abs/1405.4053), sources: [[JonathanRaiman/PVDM]](https://github.com/JonathanRaiman/PVDM), [[klb3713/sentence2vec]](https://github.com/klb3713/sentence2vec).
- **Efficient Estimation of Word Representations in Vector Space**, [[paper]](https://arxiv.org/abs/1301.3781), sources: [[word2vec]](https://code.google.com/archive/p/word2vec/).
- **Exploiting Similarities among Languages for Machine Translation**, [[paper]](https://arxiv.org/abs/1309.4168), sources: [[mostafachatillon/word2vec]](https://github.com/mostafachatillon/word2vec/tree/master/word2vec%20machine%20translation), [[n8686025/word2vec-translation-matrix]](https://github.com/n8686025/word2vec-translation-matrix).
- **Linguistic Regularities in Continuous Space Word Representations**, [[paper]](https://www.aclweb.org/anthology/N13-1090), sources: [[word2vec]](https://code.google.com/archive/p/word2vec/).
- **Statistical Language Models based on Neural Networks**, [[Mikolov's Ph.D. Thesis]](http://www.fit.vutbr.cz/~imikolov/rnnlm/thesis.pdf), [[slides]](http://www.fit.vutbr.cz/~imikolov/rnnlm/google.pdf), sources: [[mspandit/rnnlm]](https://github.com/mspandit/rnnlm).
- **word2vec Explained: Deriving Mikolov et al.’s Negative-Sampling Word-Embedding Method**, [[paper]](https://arxiv.org/abs/1402.3722).
- **word2vec Parameter Learning Explained**, [[paper]](https://arxiv.org/abs/1411.2738).
- **Better Word Representations with Recursive Neural Networks for Morphology**, [[paper]](https://nlp.stanford.edu/~lmthang/data/papers/conll13_morpho.pdf).
- **Linear Algebraic Structure of Word Senses, with Applications to Polysemy**, [[paper]](https://arxiv.org/abs/1601.03764), sources: [[YingyuLiang/SemanticVector]](https://github.com/YingyuLiang/SemanticVector).

### Machine/Reading Comprehension, Question Answering, Natural Language Understanding
- **SQuAD 100,000+ Questions for Machine Comprehension of Text**, [[paper]](https://arxiv.org/abs/1606.05250), [[homepage - SQuAD]](https://rajpurkar.github.io/SQuAD-explorer/).
- **Query-Reduction Networks for Question Answering**, [[paper]](https://arxiv.org/abs/1606.04582), [[blog]](http://uwnlp.github.io/qrn/), sources: [[uwnlp/qrn]](https://github.com/uwnlp/qrn).
- **Bi-Directional Attention Flow for Machine Comprehension**, [[paper]](https://arxiv.org/abs/1611.01603), [[homepage]](https://allenai.github.io/bi-att-flow/), [[demo]](http://allgood.cs.washington.edu:1995), sources: [[allenai/bi-att-flow]](https://github.com/allenai/bi-att-flow).
- **Reading Wikipedia to Answer Open-Domain Questions**, [[paper]](https://arxiv.org/abs/1704.00051), sources: [[facebookresearch/DrQA]](https://github.com/facebookresearch/DrQA), [[hitvoice/DrQA]](https://github.com/hitvoice/DrQA).
- **R-Net: Machine Reading Comprehension with Self-matching Networks**, [[paper]](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/r-net.pdf), [[blog]](http://yerevann.github.io/2017/08/25/challenges-of-reproducing-r-net-neural-network-using-keras/), sources: [[HKUST-KnowComp/R-Net]](https://github.com/HKUST-KnowComp/R-Net), [[YerevaNN/R-NET-in-Keras]](https://github.com/YerevaNN/R-NET-in-Keras), [[minsangkim142/R-net]](https://github.com/minsangkim142/R-net).
- **Simple and Effective Multi-Paragraph Reading Comprehension**, [[paper]](https://arxiv.org/abs/1710.10723), sources: [[allenai/document-qa]](https://github.com/allenai/document-qa).
- **TriviaQA: A Large Scale Distantly Supervised Challenge Dataset for Reading Comprehension**, [[paper]](https://arxiv.org/abs/1705.03551), [[homepage]](http://nlp.cs.washington.edu/triviaqa/), sources: [[mandarjoshi90/triviaqa]](https://github.com/mandarjoshi90/triviaqa).
- **Large-scale Cloze Test Dataset Designed by Teachers**, [[paper]](https://arxiv.org/abs/1711.03225), [[homepage]](http://www.qizhexie.com), sources: [[qizhex/Large-scale-Cloze-Test-Dataset-Designed-by-Teachers]](https://github.com/qizhex/Large-scale-Cloze-Test-Dataset-Designed-by-Teachers).
- **Attention is All You Need**, [[paper]](https://arxiv.org/abs/1706.03762), sources: [[Kyubyong/transformer]](https://github.com/Kyubyong/transformer), [[jadore801120/attention-is-all-you-need-pytorch]](https://github.com/jadore801120/attention-is-all-you-need-pytorch).
- **Making Neural QA as Simple as Possible but not Simpler**, [[paper]](https://arxiv.org/abs/1703.04816), [[homepage]](https://dirkweissenborn.github.io/publications.html), [[github-page]](https://github.com/georgwiese), sources: [[georgwiese/biomedical-qa]](https://github.com/georgwiese/biomedical-qa).
- **A Thorough Examination of the CNN/Daily Mail Reading Comprehension Task**, [[paper]](https://arxiv.org/abs/1606.02858), sources: [[danqi/rc-cnn-dailymail]](https://github.com/danqi/rc-cnn-dailymail).
- **An End-to-End Model for Question Answering over Knowledge Base with Cross-Attention Combining Global Knowledge**, [[paper]](https://arxiv.org/abs/1606.00979), [[homepage]](http://www.nlpr.ia.ac.cn/cip/~liukang/index.html), [[blog]](http://blog.csdn.net/LAW_130625/article/details/78484866).
- **Dynamic Integration of Background Knowledge in Neural NLU Systems**, [[paper]](https://arxiv.org/abs/1706.02596), [[homepage]](https://dirkweissenborn.github.io/publications.html).
- **Knowledge Representation and Question Answering**, [[Handbook of Knowledge Representation - Chapter 20]](https://pdfs.semanticscholar.org/d0fc/5473d4fa1f9dff0829b0dd8f780220da33c3.pdf).
- **Question Answering**, [[Speech and Language Processing 2017 - Chapter 28]](https://web.stanford.edu/~jurafsky/slp3/28.pdf).
- **LSTM-based Deep Learning Models for Non-factoid Answer Selection**, [[paper]](https://arxiv.org/abs/1511.04108), sources: [[Alan-Lee123/answer-selection]](https://github.com/Alan-Lee123/answer-selection), [[tambetm/allenAI]](https://github.com/tambetm/allenAI).
- **Two-Stage Synthesis Networks for Transfer Learning in Machine**, [[paper]](https://arxiv.org/abs/1706.09789), sources: [[davidgolub/QuestionGeneration]](https://github.com/davidgolub/QuestionGeneration).
- **World Knowledge for Reading Comprehension: Rare Entity Prediction with Hierarchical LSTMs Using External Descriptions**, [[paper]](http://aclweb.org/anthology/D17-1086), [[homepage]](http://dataset.cs.mcgill.ca/downloads/rare_entity_dataset.html).
- **An Attention-Based Word-Level Interaction Model: Relation Detection for Knowledge Base Question Answering**, [[paper]](https://arxiv.org/abs/1801.09893).
- **Teaching Machines to Read and Comprehend**, [[paper]](https://papers.nips.cc/paper/5945-teaching-machines-to-read-and-comprehend.pdf), sources: [[thomasmesnard/DeepMind-Teaching-Machines-to-Read-and-Comprehend]](https://github.com/thomasmesnard/DeepMind-Teaching-Machines-to-Read-and-Comprehend).
- **MaskGAN: Better Text Generation via Filling in the `______`**, [[paper]](https://arxiv.org/abs/1801.07736).
- **Constructing Datasets for Multi-hop Reading Comprehension Across Documents**, [[paper]](https://arxiv.org/abs/1710.06481).
- **Deep Learning for Answer Sentence Selection**, [[paper]](https://arxiv.org/pdf/1412.1632.pdf), sources: [[brmson/Sentence-selection]](https://github.com/brmson/Sentence-selection).
- **Multi-attention Recurrent Network for Human Communication Comprehension**, [[paper]](https://arxiv.org/abs/1802.00923).
- **FusionNet: Fusing via Fully-aware Attention with Application to Machine Comprehension**, [[paper]](https://arxiv.org/abs/1711.07341), sources: [[exe1023/FusionNet]](https://github.com/exe1023/FusionNet), [[momohuang/FusionNet-NLI]](https://github.com/momohuang/FusionNet-NLI).
- **Improved Neural Relation Detection for Knowledge Base Question Answering**, [[paper]](https://arxiv.org/abs/1704.06194).

#### Memory Network
- **Memory Networks**, [[paper]](https://arxiv.org/abs/1410.3916), sources: [[facebook/MemNN]](https://github.com/facebook/MemNN).
- **End-To-End Memory Networks**, [[paper]](https://arxiv.org/abs/1503.08895), sources: [[facebook/MemNN]](https://github.com/facebook/MemNN), [[seominjoon/memnn-tensorflow]](https://github.com/seominjoon/memnn-tensorflow), [[domluna/memn2n]](https://github.com/domluna/memn2n), [[carpedm20/MemN2N-tensorflow]](https://github.com/carpedm20/MemN2N-tensorflow).
- **Dynamic Memory Networks for Visual and Textual Question Answering**, [[paper]](https://arxiv.org/abs/1603.01417), [[blog]](https://yerevann.github.io/2016/02/05/implementing-dynamic-memory-networks/), sources: [[IsaacChanghau/AmusingPythonCodes/dmn]](https://github.com/IsaacChanghau/AmusingPythonCodes/tree/master/dmn), [[therne/dmn-tensorflow]](https://github.com/therne/dmn-tensorflow), [[barronalex/Dynamic-Memory-Networks-in-TensorFlow]](https://github.com/barronalex/Dynamic-Memory-Networks-in-TensorFlow), [[ethancaballero/Improved-Dynamic-Memory-Networks-DMN-plus]](https://github.com/ethancaballero/Improved-Dynamic-Memory-Networks-DMN-plus), [[dandelin/Dynamic-memory-networks-plus-Pytorch]](https://github.com/dandelin/Dynamic-memory-networks-plus-Pytorch), [[DeepRNN/visual_question_answering]](https://github.com/DeepRNN/visual_question_answering).
- **Ask Me Anything: Dynamic Memory Networks for Natural Language Processing**, [[paper]](https://arxiv.org/abs/1506.07285), sources: [[DongjunLee/dmn-tensorflow]](https://github.com/DongjunLee/dmn-tensorflow).
- **Towards AI-Complete Question Answering: a Set of Prerequisite Toy Tasks**, [[paper]](https://arxiv.org/abs/1502.05698).

### Knowledge Base Representation / Knowledge Representation Learning
- **Reasoning With Neural Tensor Networks for Knowledge Base Completion**, [[paper]](https://nlp.stanford.edu/pubs/SocherChenManningNg_NIPS2013.pdf), sources: [[siddharth-agrawal/Neural-Tensor-Network]](https://github.com/siddharth-agrawal/Neural-Tensor-Network).
- **Knowledge Graph Completion with Adaptive Sparse Transfer Matrix**, [[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/11982/11693), sources: [[FrankWork/transparse]](https://github.com/FrankWork/transparse), [[thunlp/Fast-TransX]](https://github.com/thunlp/Fast-TransX).
- **PTransE: Modeling Relation Paths for Representation Learning of Knowledge Bases**, [[paper]](https://arxiv.org/abs/1506.00379), [[homepage]](https://github.com/thunlp), sources: [[thunlp/Fast-TransX]](https://github.com/thunlp/Fast-TransX).
- **TransE: Translating Embeddings for Modeling Multi-relational Data**, [[paper]](https://papers.nips.cc/paper/5071-translating-embeddings-for-modeling-multi-relational-data.pdf), sources: [[thunlp/TensorFlow-TransX]](https://github.com/thunlp/TensorFlow-TransX).
- **TransH: Knowledge Graph Embedding by Translating on Hyperplanes**, [[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/view/8531/8546), sources: [[thunlp/TensorFlow-TransX]](https://github.com/thunlp/TensorFlow-TransX).
- **TransR: Learning Entity and Relation Embeddings for Knowledge Graph Completion**, [[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9571/9523), sources: [[thunlp/TensorFlow-TransX]](https://github.com/thunlp/TensorFlow-TransX).
- **TransD: Knowledge Graph Embedding via Dynamic Mapping Matrix**, [[paper]](http://www.aclweb.org/anthology/P15-1067), sources: [[thunlp/TensorFlow-TransX]](https://github.com/thunlp/TensorFlow-TransX).
- **RelNet: End-to-End Modeling of Entities & Relations**, [[paper]](https://arxiv.org/abs/1706.07179), [[homepage]](http://thetb.github.io).

### Semantic Related

#### Slides and Introduction
- **Automatic Semantic Role Labeling**, [[slides]](https://nlp.stanford.edu/kristina/papers/SRL-Tutorial-post-HLT-NAACL-06.pdf).
- **Semantic Role Labeling**, [[doc]](https://web.stanford.edu/~jurafsky/slp3/22.pdf).
- **Part-of-Speech Tagging**, [[slides]](http://www.computational-logic.org/iccl/master/lectures/summer06/nlp/part-of-speech-tagging.pdf).
- **Introduction to the CoNLL-2005 Shared Task: Semantic Role Labeling**, [[slides]](http://www.lsi.upc.edu/~srlconll/st05/slides/intro.pdf).
- **Semantic Role Labeling Tutorial**, [[slides]](http://naacl2013.naacl.org/Documents/semantic-role-labeling-part-1-naacl-2013-tutorial.pdf).

#### Coreference/Anaphora Resolution
- **Deep Reinforcement Learning for Mention-Ranking Coreference Models**, [[paper]](https://arxiv.org/abs/1609.08667), [[blog]](https://medium.com/huggingface/state-of-the-art-neural-coreference-resolution-for-chatbots-3302365dcf30), [[demo]](https://huggingface.co/coref/), sources: [[huggingface/neuralcoref]](https://github.com/huggingface/neuralcoref), [[clarkkev/deep-coref]](https://github.com/clarkkev/deep-coref).
- **Improving Coreference Resolution by Learning Entity-Level Distributed Representations**, [[paper]](https://cs.stanford.edu/people/kevclark/resources/clark-manning-acl16-improving.pdf), sources: [[clarkkev/deep-coref]](https://github.com/clarkkev/deep-coref).
- **Issues in Anaphora Resolution**, [[doc]](https://nlp.stanford.edu/courses/cs224n/2003/fp/iqsayed/project_report.pdf).
- **Joint Entity and Event Coreference Resolution across Documents**, [[paper]](https://aclweb.org/anthology/D/D12/D12-1045.pdf).
- **Linguistic Knowledge as Memory for Recurrent Neural Networks**, [[paper]](https://arxiv.org/abs/1703.02620).

#### Semantic Role labeling
- **Introduction to the CoNLL-2005 Shared Task: Semantic Role Labeling**, [[paper]](http://www.cs.upc.edu/~srlconll/st05/papers/intro.pdf), [[homepage]](http://www.lsi.upc.edu/~srlconll/), [[homepage]](http://www.lsi.upc.edu/~srlconll/st04/st04.html).
- **Deep Semantic Role Labeling: What Works and Whats Next**, [[paper]](https://homes.cs.washington.edu/~luheng/files/acl2017_hllz.pdf), sources: [[luheng/deep_srl]](https://github.com/luheng/deep_srl).
- **End-to-end Learning of Semantic Role Labeling using RNN**, [[paper]](http://www.aclweb.org/anthology/P15-1109), sources: [[sanjaymeena/semantic_role_labeling_deep_learning]](https://github.com/sanjaymeena/semantic_role_labeling_deep_learning).
- **Neural Semantic Role Labeling with Dependency Path Embeddings**, [[paper]](https://arxiv.org/abs/1605.07515), sources: [[microth/PathLSTM]](https://github.com/microth/PathLSTM).
- **Semantic Role Labeling with Neural Network Factors**, [[paper]](http://www.aclweb.org/anthology/D15-1112).

#### Sequence Labeling
- **Bidirectional LSTM-CRF Models for Sequence Tagging**, [[paper]](https://arxiv.org/abs/1508.01991), [[blog]](https://guillaumegenthial.github.io/sequence-tagging-with-tensorflow.html), sources: [[Hironsan/anago]](https://github.com/Hironsan/anago), [[guillaumegenthial/sequence_tagging]](https://github.com/guillaumegenthial/sequence_tagging).
- **Boosting Named Entity Recognition with Neural Character Embeddings**, [[paper]](https://arxiv.org/abs/1505.05008), sources: [[isohrab/German-NER]](https://github.com/isohrab/German-NER).
- **End-to-end Sequence Labeling via Bi-directional LSTM-CNNs-CRF**, [[paper]](https://arxiv.org/abs/1603.01354), sources: [[LopezGG/NN_NER_tensorFlow]](https://github.com/LopezGG/NN_NER_tensorFlow).
- **Fast and Accurate Entity Recognition with Iterated Dilated Convolutions**, [[paper]](https://arxiv.org/abs/1702.02098), sources: [[iesl/dilated-cnn-ner]](https://github.com/iesl/dilated-cnn-ner).
- **Feature-Rich Part-of-Speech Tagging with a Cyclic Dependency Network**, [[paper]](https://nlp.stanford.edu/pubs/tagging.pdf).
- **Transfer Learning for Sequence Tagging with Hierarchical Recurrent Networks**, [[paper]](https://arxiv.org/abs/1703.06345), sources: [[kimiyoung/transfer]](https://github.com/kimiyoung/transfer).
- **Named Entity Recognition with Bidirectional LSTM-CNNs**, [[paper]](https://www.aclweb.org/anthology/Q16-1026), sources: [[ThanhChinhBK/Ner-BiLSTM-CNNs]](https://github.com/ThanhChinhBK/Ner-BiLSTM-CNNs).
- **Neural Architectures for Named Entity Recognition**, [[paper]](https://arxiv.org/abs/1603.01360), sources: [[clab/stack-lstm-ner]](https://github.com/clab/stack-lstm-ner), [[glample/tagger]](https://github.com/glample/tagger), [[marekrei/sequence-labeler]](https://github.com/marekrei/sequence-labeler).
- **Neural Models for Sequence Chunking**, [[paper]](https://arxiv.org/abs/1701.04027).
- **Optimal Hyperparameters for Deep LSTM-Networks for Sequence Labeling Tasks**, [[paper]](https://arxiv.org/abs/1707.06799), sources: [[UKPLab/emnlp2017-bilstm-cnn-crf]](https://github.com/UKPLab/emnlp2017-bilstm-cnn-crf).
- **Part-of-Speech Tagging from 97% to 100%: Is It Time for Some Linguistics?**, [[paper]](https://nlp.stanford.edu/pubs/CICLing2011-manning-tagging.pdf).
- **Part-of-Speech Tagging with Bidirectional Long Short-Term Memory Recurrent Neural Network**, [[paper]](https://arxiv.org/abs/1510.06168).
- **Multilingual Part-of-Speech Tagging with Bidirectional Long Short-Term Memory Models and Auxiliary Loss**, [[paper]](https://arxiv.org/abs/1604.05529), sources: [[bplank/bilstm-aux]](https://github.com/bplank/bilstm-aux).

#### Dependency Parser
- **A Fast and Accurate Dependency Parser using Neural Networks**, [[paper]](https://cs.stanford.edu/~danqi/papers/emnlp2014.pdf), sources: [[akjindal53244/dependency_parsing_tf]](https://github.com/akjindal53244/dependency_parsing_tf), [[ljj314zz/dependency_parsing_tf-master]](https://github.com/ljj314zz/dependency_parsing_tf-master).

#### Punctuation Restoration
- **Punctuation Prediction for Unsegmented Transcript Based on Word Vector**, [[paper]](http://www.lrec-conf.org/proceedings/lrec2016/pdf/103_Paper.pdf).
- **Bidirectional Recurrent Neural Network with Attention Mechanism for Punctuation Restoration**, [[paper]](https://pdfs.semanticscholar.org/8785/efdad2abc384d38e76a84fb96d19bbe788c1.pdf?_ga=2.156364859.1813940814.1518068648-1853451355.1518068648), sources: [[ottokart/punctuator2]](https://github.com/ottokart/punctuator2).
- **Joint Learning of Correlated Sequence Labeling Tasks Using Bidirectional Recurrent Neural Networks**, [[paper]](https://arxiv.org/pdf/1703.04650.pdf).
- **Sequence-to-Sequence Models for Punctuated Transcription Combing Lexical and Acoustic Features**, [[paper]](http://homepages.inf.ed.ac.uk/s1569734/papers/icassp-2017.pdf), sources: [[choko/acoustic_punctuation]](https://github.com/choko/acoustic_punctuation).

#### Grammatical Error Correction
- **A Multilayer Convolutional Encoder-Decoder Neural Network for Grammatical Error Correction**, [[paper]](https://arxiv.org/abs/1801.08831), [[nusnlp/mlconvgec2018]](https://github.com/nusnlp/mlconvgec2018).

### Sentiment Analysis / Stance Detection
- **Introduction to Sentiment Analysis**, [[slides]](https://lct-master.org/files/MullenSentimentCourseSlides.pdf), [[blog]](https://blog.algorithmia.com/introduction-sentiment-analysis-algorithms/).
- **OSU Twitter NLP Tools**, [[aritter/twitter_nlp]](https://github.com/aritter/twitter_nlp).
- **Multiple Instance Learning Networks for Fine-Grained Sentiment Analysis**, [[paper]](https://arxiv.org/abs/1711.09645), [[data]](https://github.com/EdinburghNLP/spot-data).
- **Multitask Learning for Fine-Grained Twitter Sentiment Analysis**, [[paper]](https://arxiv.org/abs/1707.03569), sources: [[balikasg/sigir2017]](https://github.com/balikasg/sigir2017).
- **Detecting Stance in Tweets And Analyzing its Interaction with Sentiment**, [[paper]](http://anthology.aclweb.org/S16-2021), sources: [[vishaalmohan/twitter-stance-detection]](https://github.com/vishaalmohan/twitter-stance-detection).
- **SemEval-2016 Task 6: Detecting Stance in Tweets**, [[paper]](http://www.aclweb.org/anthology/S16-1003), [[homepage]](http://alt.qcri.org/semeval2016/task6/), [[The SemEval-2016 Stance Dataset]](http://www.saifmohammad.com/WebPages/StanceDataset.htm).
- **DeepStance at SemEval-2016 Task 6: Detecting Stance in Tweets Using Character and Word-Level CNNs**, [[paper]](https://arxiv.org/abs/1606.05694).
- **Stance and Sentiment in Tweets**, [[paper]](https://arxiv.org/abs/1605.01655).
- **Topical Stance Detection for Twitter: A Two-Phase LSTM Model Using Attention**, [[paper]](https://arxiv.org/abs/1801.03032).
- **Multimodal Sentiment Analysis with Word-Level Fusion and Reinforcement Learning**, [[paper]](https://arxiv.org/abs/1802.00924), 

### Multi-Model
- **Multi-Task Cross-Lingual Sequence Tagging from Scratch**, [[paper]](https://arxiv.org/abs/1603.06270).
- **A Joint Many-Task Model: Growing a Neural Network for Multiple NLP Tasks**, [[paper]](https://arxiv.org/abs/1611.01587), [[blog]](https://theneuralperspective.com/2017/03/08/a-joint-many-task-model-growing-a-neural-network-for-multiple-nlp-tasks/), sources: [[rubythonode/joint-many-task-model]](https://github.com/rubythonode/joint-many-task-model).
- **Natural Language Processing (Almost) from Scratch**, [[paper]](https://arxiv.org/abs/1103.0398), sources: [[attardi/deepnl]](https://github.com/attardi/deepnl).

## Commonsense
- **ConceptNet 5.5: An Open Multilingual Graph of General Knowledge**, [[paper]](https://arxiv.org/abs/1612.03975), sources: [[GitHub page]](https://github.com/commonsense), [[commonsense/conceptnet5]](https://github.com/commonsense/conceptnet5), [[commonsense/conceptnet-numberbatch]](https://github.com/commonsense/conceptnet-numberbatch).
- **Representing General Relational Knowledge in ConceptNet 5**, [[paper]](http://lrec-conf.org/proceedings/lrec2012/pdf/1072_Paper.pdf).
- **Commonsense based Topic Modeling**, [[paper]](http://sentic.net/wisdom2013rajagopal.pdf).
- **Combining ConceptNet and WordNet for Word Sense Disambiguation**, [[paper]](http://www.aclweb.org/anthology/I11-1077).
- **More Accurate Question Answering on Freebase**, [[paper]](http://ad-publications.informatik.uni-freiburg.de/freebase-qa.pdf).
- **Commonsense for Machine Intelligence: Text to Knowledge and Knowledge to Text**, [[slides]](http://people.mpi-inf.mpg.de/~ntandon/presentations/cikm-2017-tutorial-commonsense/commonsense.pdf), [[CIKM 2017 Singapore Tutorials]](http://cikm2017.org/tutorialmain.html), [[Commonsense for Machine Intelligence, Allen Institute, CIKM 2017 TUTORIAL]](http://allenai.org/tutorials/csk/), [[Allen Institute]](http://allenai.org/index.html).

### Script Knowledge
- **DeScript: A Crowdsourced Corpus for the Acquisition of High-Quality Script Knowledge**, [[paper]](http://www.lrec-conf.org/proceedings/lrec2016/pdf/913_Paper.pdf).
- **Inducing Neural Models of Script Knowledge**, [[paper]](https://aclanthology.coli.uni-saarland.de/pdf/W/W14/W14-1606.pdf).
- **Inducing Script Structure from Crowdsourced Event Descriptions via Semi-Supervised Clustering**, [[paper]](http://www.coli.uni-saarland.de/~mroth/LSDSem/pdfs/LSDSem01.pdf).
- **Learning Script Knowledge with Web Experiments**, [[paper]](http://www.aclweb.org/anthology/P10-1100).
- **Open Mind Common Sense: Knowledge Acquisition from the General Public**, [[paper]](http://web.media.mit.edu/~lieber/Teaching/Common-Sense-Course-02/Open-Mind-AAAI2002.pdf).
- **Unsupervised Learning of Narrative Event Chains**, [[paper]](https://www.aclweb.org/anthology/P/P08/P08-1090.pdf).
- **LSDSem 2017: 2nd Workshop on Linking Models of Lexical, Sentential and Discourse-level Semantics**, [[homepage]](http://www.coli.uni-saarland.de/~mroth/LSDSem/), [[doc]](https://pdfs.semanticscholar.org/13da/c5f2d76b630307cc590efb898639c6c21245.pdf?_ga=2.115348101.2032186556.1517662608-872936552.1517662608).

## Deep Learning

### Recurrent Neural Networks
- **An Empirical Exploration of Recurrent Network Architectures**, [[paper]](http://proceedings.mlr.press/v37/jozefowicz15.pdf).
- **Empirical Evaluation of Gated Recurrent Neural Network on Sequence Modeling**, [[paper]](https://arxiv.org/abs/1412.3555).
- **Feed-forward Networks with Attention can Solve Some Long-term Memory Problems**, [[paper]](https://arxiv.org/abs/1512.08756).
- **Grid Long Short-Term Memory**, [[paper]](https://arxiv.org/abs/1507.01526).
- **Learning to Forget Continual Prediction with LSTM**, [[paper]](https://pdfs.semanticscholar.org/1154/0131eae85b2e11d53df7f1360eeb6476e7f4.pdf).
- **Long Short-Term Memory**, [[paper]](http://www.bioinf.jku.at/publications/older/2604.pdf).
- **LSTM: A Search Space Odyssey**, [[paper]](https://arxiv.org/abs/1503.04069).
- **Long Short-Term Memory in Recurrent Neural Networks**, [[Gers' Ph.D. Thesis]](https://www.researchgate.net/profile/Felix_Gers/publication/2562741_Long_Short-Term_Memory_in_Recurrent_Neural_Networks/links/5759410a08ae9a9c954e77f5.pdf).
- **Recurrent Neural Network Regularization**, [[paper]](https://arxiv.org/abs/1409.2329).
- **Supervised Sequence Labelling with Recurrent Neural Networks**, [[Alex Graves's Ph.D. Thesis]](https://www.cs.toronto.edu/~graves/preprint.pdf).
- **Visualizing and Understanding Curriculum Learning for Long Short-Term Memory Networks**, [[paper]](https://arxiv.org/abs/1611.06204).
- **Nested LSTMs**, [[paper]](https://arxiv.org/abs/1801.10308), sources: [[hannw/nlstm]](https://github.com/hannw/nlstm).

### Optimizations
- **Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification**, [[paper]](https://arxiv.org/abs/1502.01852), [[Kaiming He's homepage]](http://kaiminghe.com), sources: [[nutszebra/prelu_net]](https://github.com/nutszebra/prelu_net).
- **Fast and Accurate Deep Network Learning by Exponential Linear Units (ELUs)**, [[paper]](https://arxiv.org/abs/1511.07289).
- **Self-Normalizing Neural Networks**, [[paper]](https://arxiv.org/abs/1706.02515), sources: [[IsaacChanghau/AmusingPythonCodes/selu_activation_visualization]](https://github.com/IsaacChanghau/AmusingPythonCodes/tree/master/selu_activation_visualization), [[shaohua0116/Activation-Visualization-Histogram]](https://github.com/shaohua0116/Activation-Visualization-Histogram), [[bioinf-jku/SNNs]](https://github.com/bioinf-jku/SNNs), [[IsaacChanghau/AmusingPythonCodes/snns]](https://github.com/IsaacChanghau/AmusingPythonCodes/tree/master/snns).
- **Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift**, [[paper]](https://arxiv.org/abs/1502.03167), sources: [[IsaacChanghau/AmusingPythonCodes/batch_normalization]](https://github.com/IsaacChanghau/AmusingPythonCodes/tree/master/batch_normalization), [[tomokishii/mnist_cnn_bn.py]](https://gist.github.com/tomokishii/0ce3bdac1588b5cca9fa5fbdf6e1c412).
- **Layer Normalization**, [[paper]](https://arxiv.org/abs/1607.06450), sources: [[ryankiros/layer-norm]](https://github.com/ryankiros/layer-norm), [[pbhatia243/tf-layer-norm]](https://github.com/pbhatia243/tf-layer-norm), [[NickShahML/tensorflow_with_latest_papers]](https://github.com/NickShahML/tensorflow_with_latest_papers).
- **Recurrent Batch Normalization**, [[paper]](https://arxiv.org/abs/1603.09025), sources: [[cooijmanstim/recurrent-batch-normalization]](https://github.com/cooijmanstim/recurrent-batch-normalization), [[jihunchoi/recurrent-batch-normalization-pytorch]](https://github.com/jihunchoi/recurrent-batch-normalization-pytorch).
- **Dropout: A Simple Way to Prevent Neural Networks from Overfitting**, [[paper]](http://jmlr.org/papers/volume15/srivastava14a.old/srivastava14a.pdf).
- **Maxout Networks**, [[paper]](https://arxiv.org/pdf/1302.4389.pdf), sources: [[philipperemy/tensorflow-maxout]](https://github.com/philipperemy/tensorflow-maxout).
- **An overview of gradient descent optimization algorithms**, [[paper]](https://arxiv.org/abs/1609.04747).
- **Curriculum Learning**, [[paper]](https://ronan.collobert.com/pub/matos/2009_curriculum_icml.pdf).
- **Incorporating Nesterov Momentum into Adam**, [[paper]](https://openreview.net/pdf?id=OM0jvwB8jIp57ZJjtNEZ).
- **On Optimization Methods for Deep Learning**, [[paper]](http://ai.stanford.edu/~quocle/LeNgiCoaLahProNg11.pdf), [[homepage]](http://www.andrewng.org/portfolio/on-optimization-methods-for-deep-learning/).
- **Understanding the difficulty of training deep feedforward neural networks**, [[paper]](http://proceedings.mlr.press/v9/glorot10a/glorot10a.pdf).

### Neural Turing Machines
- **Neural Turing Machines**, [[paper]](https://arxiv.org/abs/1410.5401), sources: [[carpedm20/NTM-tensorflow]](https://github.com/carpedm20/NTM-tensorflow).

### Capsules
- **Dynamic Routing Between Capsules**, [[paper]](https://arxiv.org/abs/1710.09829), [[blog]](https://jhui.github.io/2017/11/03/Dynamic-Routing-Between-Capsules/), sources: [[soskek/dynamic_routing_between_capsules]](https://github.com/soskek/dynamic_routing_between_capsules), [[naturomics/CapsNet-Tensorflow]](https://github.com/naturomics/CapsNet-Tensorflow), [[XifengGuo/CapsNet-Keras]](https://github.com/XifengGuo/CapsNet-Keras).

### Generative Adversarial Networks
- **Generative Adversarial Nets**, [[paper]](https://arxiv.org/abs/1406.2661), sources: [[IsaacChanghau/AmusingPythonCodes/generative_adversarial_nets]](https://github.com/IsaacChanghau/AmusingPythonCodes/tree/master/generative_adversarial_nets), [[aymericdamien/TensorFlow-Examples]](https://github.com/aymericdamien/TensorFlow-Examples).
- **Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks**, [[paper]](https://arxiv.org/abs/1511.06434), sources: [[Newmu/dcgan_code]](https://github.com/Newmu/dcgan_code).
- **SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient**, [[paper]](https://arxiv.org/abs/1609.05473), sources:[[LantaoYu/SeqGAN]](https://github.com/LantaoYu/SeqGAN).

### Highway Networks
- **Highway Networks**, [[paper]](https://arxiv.org/abs/1505.00387), sources: [[IsaacChanghau/AmusingPythonCodes/highway_networks]](https://github.com/IsaacChanghau/AmusingPythonCodes/tree/master/highway_networks), [[lucko515/fully-connected-highway-network]](https://github.com/lucko515/fully-connected-highway-network), [[fomorians/highway-cnn]](https://github.com/fomorians/highway-cnn).
- **Recurrent Highway Networks**, [[paper]](https://arxiv.org/abs/1607.03474), sources: [[IsaacChanghau/AmusingPythonCodes/highway_networks]](https://github.com/IsaacChanghau/AmusingPythonCodes/tree/master/highway_networks), [[julian121266/RecurrentHighwayNetworks]](https://github.com/julian121266/RecurrentHighwayNetworks).
- **Training Very Deep Networks**, [[paper]](https://arxiv.org/abs/1507.06228), sources: [[trangptm/HighwayNetwork]](https://github.com/trangptm/HighwayNetwork).

### Convolutional Networks
- **Densely Connected Convolutional Networks**, [[paper]](https://arxiv.org/abs/1608.06993).
- **Going Deeper with Convolutions**, [[paper]](https://arxiv.org/abs/1409.4842).
- **ImageNet Classification with Deep Convolutional Neural Networks**, [[paper]](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf).
- **Learning Convolutional Neural Networks for Graphs**, [[paper]](https://arxiv.org/abs/1605.05273).
- **Very Deep Convolutional Networks for Large-Scale Image Recognition**, [[paper]](https://arxiv.org/abs/1409.1556).
- **Visualizing and Understanding Convolutional Networks**, [[paper]](https://arxiv.org/abs/1311.2901).

### Residual Networks
- **Deep Residual Learning for Image Recognition**, [[paper]](https://arxiv.org/abs/1512.03385), sources: [[IsaacChanghau/AmusingPythonCodes/resnet]](https://github.com/IsaacChanghau/AmusingPythonCodes/tree/master/resnet), [[wenxinxu/resnet-in-tensorflow]](https://github.com/wenxinxu/resnet-in-tensorflow).
- **Residual Networks for Tiny ImageNet**, [[paper]](http://cs231n.stanford.edu/reports/2016/pdfs/411_Report.pdf).

### Multi-Model
- **One Model To Learn Them All**, [[paper]](https://arxiv.org/abs/1706.05137), [[blog]](https://blog.acolyer.org/2018/01/12/one-model-to-learn-them-all/).
- **Show and Tell: Lessons learned from the 2015 MSCOCO Image Captioning Challenge**, [[paper]](https://arxiv.org/abs/1609.06647), sources: [[tensorflow/models/im2txt]](https://github.com/tensorflow/models/tree/master/research/im2txt).

## Reinforcement Learning
- **Playing Atari with Deep Reinforcement Learning**, [[paper]](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf), [[blog]](https://keon.io/deep-q-learning/), sources: [[kuz/DeepMind-Atari-Deep-Q-Learner]](https://github.com/kuz/DeepMind-Atari-Deep-Q-Learner).
