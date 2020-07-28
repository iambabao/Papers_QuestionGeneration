# Paper List of Question Generation

- [Paper List of Question Generation](#paper-list-of-question-generation)
  - [Survey](#survey)
  - [Basic QG](#basic-qg)
    - [2017](#2017)
    - [2018](#2018)
    - [2019](#2019)
  - [Question Type & Answer Modeling](#question-type--answer-modeling)
    - [2018](#2018-1)
    - [2019](#2019-1)
  - [Paragraph Level](#paragraph-level)
    - [2018](#2018-2)
    - [2019](#2019-2)
  - [Conversational QG](#conversational-qg)
    - [2018](#2018-3)
  - [KB QG](#kb-qg)
    - [2016](#2016)
    - [2017](#2017-1)
    - [2018](#2018-4)
  - [Open QG](#open-qg)
    - [2019](#2019-3)
  - [Visiual QG](#visiual-qg)
    - [2018](#2018-5)
  - [Others](#others)
    - [2018](#2018-6)

---

## Survey
[:arrow_up:](#paper-list-of-question-generation)

<details>
<summary>
<a href="https://github.com/">Paper Name</a>, Conference
<i>Author list</i>
</summary>
<blockquote><p align="justify">
Details.
</p></blockquote>
</details>

## Basic QG
[:arrow_up:](#paper-list-of-question-generation)

### 2017

<details>
<summary>
<a href="https://www.aclweb.org/anthology/P17-1123.pdf">Learning to Ask: Neural Question Generation for Reading Comprehension</a>, ACL
<i>Xinya Du, Junru Shao, Claire Cardie</i>
</summary>
<blockquote><p align="justify">
Dataset: SQuAD. Seq2Seq. Both sentence level and paragraph level.
</p></blockquote>
</details>

<details>
<summary>
<a href="https://www.aclweb.org/anthology/D17-1219.pdf">Identifying Where to Focus in Reading Comprehension for Neural Question Generation</a>, EMNLP
<i>Xinya Du, Claire Cardie</i>
</summary>
<blockquote><p align="justify">
Dataset: SQuAD. Use a tagging model to select question-worthy sentence. Seq2Seq model for question generation. No answer span.
</p></blockquote>
</details>

<details>
<summary>
<a href="http://tcci.ccf.org.cn/conference/2017/papers/1084.pdf">Neural Question Generation from Text_A Preliminary Study</a>, NLPCC
<i>Qingyu Zhou, Nan Yang, Furu Wei, Chuanqi Tan, Hangbo Bao, Ming Zhou</i>
</summary>
<blockquote><p align="justify">
Dataset: SQuAD.
</p></blockquote>
</details>

### 2018

<details>
<summary>
<a href="https://www.aclweb.org/anthology/W18-2609.pdf">Neural Models for Key Phrase Extraction and Question Generation</a>, ACL-WS
<i>Sandeep Subramanian, Tong Wang, Xingdi Yuan, Adam Trischler</i>
</summary>
<blockquote><p align="justify">
Dataset: SQuAD. Use Pointer Network for key phrase extraction. Propose a multi-span F1 score.
</p></blockquote>
</details>

### 2019

<details>
<summary>
<a href="https://www.aclweb.org/anthology/P19-1415.pdf">Learning to Ask Unanswerable Questions for Machine Reading Comprehension</a>, ACL
<i>Haichao Zhu, Li Dong, Furu Wei, Wenhui Wang, Bing Qin, Ting Liu</i>
</summary>
<blockquote><p align="justify">
Dataset: SQuAD. Generate unanswerable question.
</p></blockquote>
</details>

## Question Type & Answer Modeling
[:arrow_up:](#paper-list-of-question-generation)

### 2018

<details>
<summary>
<a href="https://www.aclweb.org/anthology/D18-1427.pdf">Answer-focused and Position-aware Neural Question Generation</a>, EMNLP
<i>Xingwu Sun, Jing Liu, Yajuan Lyu, Wei He, Yanjun Ma, Shi Wang</i>
</summary>
<blockquote><p align="justify">
Dataset: SQuAD. Add a question word vocabulary for question type.
</p></blockquote>
</details>

<details>
<summary>
<a href="https://openreview.net/pdf?id=rkRR1ynIf">Aspect-Based Question Generation</a>, ICLR-WS
<i>Wenpeng Hu, Bing Liu, Jinwen Ma, Dongyan Zhao, Rui Yan</i>
</summary>
<blockquote><p align="justify">
Dataset: AQAD. Aspect and question type.
</p></blockquote>
</details>

<details>
<summary>
<a href="https://www.ijcai.org/Proceedings/2018/0632.pdf">Teaching Machines to Ask Questions</a>, IJCAI
<i>Kaichun Yao, Libo Zhang, Tiejian Luo, Lili Tao, Yanjun Wu</i>
</summary>
<blockquote><p align="justify">
Dataset: SQuAD. Use latent variables to model the distribution of question type. GAN + RL.
</p></blockquote>
</details>

<details>
<summary>
<a href="https://www.aclweb.org/anthology/N18-2090.pdf">Leveraging Context Information for Natural Question Generation</a>, NAACL
<i>Linfeng Song, Zhiguo Wang, Wael Hamza, Yue Zhang, Daniel Gildea</i>
</summary>
<blockquote><p align="justify">
Dataset: SQuAD. Match context vector with question representation.
</p></blockquote>
</details>

### 2019

<details>
<summary>
<a href="https://www.aaai.org/ojs/index.php/AAAI/article/view/4629">Improving Neural Question Generation Using Answer Separation</a>, AAAI
<i>Yanghoon Kim, Hwanhee Lee, Joongbo Shin, Kyomin Jung</i>
</summary>
<blockquote><p align="justify">
Dataset: SQuAD. Take answer from passage and use two separate encoder for passage and answer. Use attention to select key information from answer. Use retrieval style word generator.
</p></blockquote>
</details>

## Paragraph Level
[:arrow_up:](#paper-list-of-question-generation)

### 2018

<details>
<summary>
<a href="https://www.aclweb.org/anthology/P18-1177.pdf">Harvesting Paragraph-Level Question-Answer Pairs from Wikipedia</a>, ACL
<i>Xinya Du, Claire Cardie</i>
</summary>
<blockquote><p align="justify">
Dataset: SQuAD. Use a tagging model to select answer. Seq2Seq model with coreference resolution for question generation. Release a 1M QA data.
</p></blockquote>
</details>

<details>
<summary>
<a href="https://www.aclweb.org/anthology/D18-1424.pdf">Paragraph-level Neural Question Generation with Maxout Pointer and Gated Self-attention Networks</a>, EMNLP
<i>Yao Zhao, Xiaochuan Ni, Yuanyuan Ding, Qifa Ke</i>
</summary>
<blockquote><p align="justify">
Dataset: SQuAD. Fusion gate and maxout pointer mechanism.
</p></blockquote>
</details>

### 2019

<details>
<summary>
<a href="https://www.aclweb.org/anthology/P19-1224.pdf">Generating Question-Answer Hierarchies</a>, ACL
<i>Kalpesh Krishna, Mohit Iyyer</i>
</summary>
<blockquote><p align="justify">
Propose a new dataset SQUASH for hierarchical question generation. SQUASH represents document as QA pairs with hierarchical information.
</p></blockquote>
</details>

## Conversational QG
[:arrow_up:](#paper-list-of-question-generation)

### 2018

<details>
<summary>
<a href="https://www.aclweb.org/anthology/P18-1204.pdf">Learning to Ask Questions in Open-domain Conversational Systems with Typed Decoders</a>, ACL
<i>Yansen Wang, Chenyi Liu, Minlie Huang, Liqiang Nie</i>
</summary>
<blockquote><p align="justify">
Divide words into three difference type: interrorgative, topic word and ordinary word. The final distribution is weighted by different types.
</p></blockquote>
</details>

## KB QG
[:arrow_up:](#paper-list-of-question-generation)

### 2016

<details>
<summary>
<a href="https://www.aclweb.org/anthology/P16-1056.pdf">Generating Factoid Questions With Recurrent Neural Networks: The 30M Factoid Question-Answer Corpus</a>, ACL
<i>Iulian Vlad Serban, Alberto García-Durán, Caglar Gulcehre, Sungjin Ahn, Sarath Chandar, Aaron Courville, Yoshua Bengio</i>
</summary>
<blockquote><p align="justify">
Dataset: SimpleQuestion, FreeBase. Seq2Seq with TransE, attention and placeholder. Release a 30M QA corpus.
</p></blockquote>
</details>

### 2017

<details>
<summary>
<a href="https://www.aclweb.org/anthology/E17-1036.pdf">Generating Natural Language Question-Answer Pairs from a Knowledge Graph Using a RNN Based Question Generation Model</a>, EACL
<i>Mitesh M. Khapra, Dinesh Raghu, Sachindra Joshi, Sathish Reddy</i>
</summary>
<blockquote><p align="justify">
Dataset: Community QA. Seq2Seq.
</p></blockquote>
</details>

### 2018

<details>
<summary>
<a href="https://www.aclweb.org/anthology/N18-1020.pdf">Zero-Shot Question Generation from Knowledge Graphs for Unseen Predicates and Entity Types</a>, NAACL
<i>Hady ElSahar, Christophe Gravier, Frédérique Laforest</i>
</summary>
<blockquote><p align="justify">
Dataset: SimpleQuestions. Seq2Seq with textual information. POS copy mechanism.
</p></blockquote>
</details>

## Open QG
[:arrow_up:](#paper-list-of-question-generation)

### 2019

<details>
<summary>
<a href="https://www.aclweb.org/anthology/P19-1497.pdf">Asking the Crowd: Question Analysis, Evaluation and Generation for Open Discussion on Online Forums</a>, ACL
<i>Zi Chai, Xinyu Xing, Xiaojun Wan, Bo Huang</i>
</summary>
<blockquote><p align="justify">
Analyze how language use affect the open-answered question. Based on the data analysis, this paper proposes some language use features that will greatly affects the answer receives. Dataset OQGenD is released for open question generation.
</p></blockquote>
</details>

## Visiual QG
[:arrow_up:](#paper-list-of-question-generation)

### 2018

<details>
<summary>
<a href="https://www.aclweb.org/anthology/C18-1150.pdf">A Reinforcement Learning Framework for Natural Question Generation using Bi-discriminators</a>, COLING
<i>Zhihao Fan, Zhongyu Wei, Shouxin Wang, Yang P. Liu, Xuanjing Huang</i>
</summary>
<blockquote><p align="justify">
TODO
</p></blockquote>
</details>

## Others
[:arrow_up:](#paper-list-of-question-generation)

### 2018

<details>
<summary>
<a href="https://www.aclweb.org/anthology/D18-1429.pdf">Towards a Better Metric for Evaluating Question Generation Systems</a>, EMNLP
<i>Preksha Nema, Mitesh M. Khapra</i>
</summary>
<blockquote><p align="justify">
Propose a new metric for modling the answerability of generated question. The proposed answerability is the weighted F1 score of different types of information. It can be add to any current metric, but need to rune the weights manually.
</p></blockquote>
</details>
