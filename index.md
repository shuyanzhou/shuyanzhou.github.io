---
layout: default
---

<!-- ## About Me -->
<a id="about-me"></a>
Hi, I’m Shuyan, a final-year PhD student of the Language Technologies Institute at [Carnegie Mellon University](https://www.cmu.edu). I am fortunately advised by Professor [Graham Neubig](http://phontron.com). Before that, I received my bachelor degree in Computer Science and Technology from Harbin Institute of Technology.

I work on building autonomous agents that could understand high-level language commands. My goal is to create AI agents that would free human beings from tedious tasks and aid them in better decision makings.

We proposed an intuitive formalism for representing [procedures as programs](https://arxiv.org/pdf/2109.08214.pdf) and subsequently applied this concept to broader tasks with large language models ([PaL](https://arxiv.org/pdf/2211.10435.pdf), [CoCoGen](https://arxiv.org/pdf/2210.07128.pdf)).
We built the first large-scale [hierarchical procedural knowledge base](https://arxiv.org/pdf/2203.07264.pdf). To learn from the knowledge base and generate new and previously unseen procedures, we designed [DocPrompting](https://arxiv.org/pdf/2207.05987.pdf) that reads the relevant documentation before taking actions.
With the belief of "what I don't measure, I can't improve", we built [WebArena](https://webarena.dev), a realistic and reproducible environment for building and evaluating autonomous agents that are guided by high-level natural language commands.

I am best reached by email at [shuyanzh@cs.cmu.edu](mailto:shuyanzh@cs.cmu.edu).

<span style="color:red">I'm on the faculty job market!</span>
<!-- Feel free to reach out about my research or anything else I might be able to help with. I’m always happy to answer questions about getting started with NLP research and applying to Ph.D. programs, especially for underrepresented groups like women, LGBTQ+. -->

<!-- Outside research, I enjoy bouldering (20% of my self-defined progress bar), playing tennis (30%), snowboarding (10%), rap (1%) and stand-up comedy (1%). I also play pingpong (80%) and basketball (70%).  -->


------------

## Publications
*\* indicates equal contribution*, *^ indicates mentorship*

**WebArena: A Realistic Web Environment for Building Autonomous Agents** \
**Shuyan Zhou**\*, Frank F. Xu\*, Hao Zhu, Xuhui Zhou, Robert Lo, Abishek Sridhar, Xianyi Cheng, Yonatan Bisk, Daniel Fried, Uri Alon, Graham Neubig \
preprint \
[[Paper](https://arxiv.org/pdf/2307.13854.pdf)][[Project Site](https://webarena.dev)][[Twitter](https://twitter.com/shuyanzhxyc/status/1683917253597855744?s=20)]


**DocPrompting: Generating Code by Retrieving the Docs** \
**Shuyan Zhou**, Uri Alon, Frank F. Xu, Zhiruo Wang, Zhengbao Jiang, Graham Neubig \
ICLR, 2023 (<span style="color:red">spotlight</span>)\
[[Paper]](https://arxiv.org/pdf/2207.05987.pdf) [[Code+Data](https://github.com/shuyanzhou/docprompting)]

**PaL: Program-aided Language Models** \
Luyu Gao\*, Aman Madaan\*, **Shuyan Zhou**\*, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan, Graham Neubig \
ICML, 2023 \
[[Paper](https://arxiv.org/pdf/2211.10435.pdf)][[Project Site](https://reasonwithpal.com)][[Twitter](https://twitter.com/shuyanzhxyc/status/1595140404545933313?s=20&t=a8GaJT23kFEPLKujdQO2IQ)][[Demo](https://huggingface.co/spaces/JavaFXpert/gpt-math-techniques)]

**Hierarchical Prompting Assists Large Language Model on Web Navigation** \
Abishek Sridhar\*, Robert Lo\*, Frank F. Xu, Hao Zhu, **Shuyan Zhou^** \
Findings of EMNLP, 2023 \
[[Paper](https://arxiv.org/pdf/2305.14257.pdf)][[Code](https://github.com/robert1003/ash-prompting)]

**CodeBERTScore: Evaluating Code Generation with Pretrained Models of Code** \
**Shuyan Zhou**\*, Uri Alon\*, Sumit Agarwal, Graham Neubig \
EMNLP 2023 \
Deep Learning for Code Workshop at ICLR, 2023 (<span style="color:red">spotlight</span>) \
[[Paper](https://arxiv.org/pdf/2302.05527.pdf)][[Code](https://github.com/neulab/code-bert-score)]

**Execution-Based Evaluation for Open-Domain Code Generation** \
Zhiruo Wang, **Shuyan Zhou**, Daniel Fried, Graham Neubig \
Findings of EMNLP, 2023 \
[[Paper](https://arxiv.org/pdf/2212.10481.pdf)][[Project Site](https://code-eval.github.io)]

**Causal Reasoning of Entities and Events in Procedural Texts** \
Li Zhang\*, Hainiu Xu\*, Yue Yang, **Shuyan Zhou**, Weiqiu You, Manni Arora, Chris Callison-Burch \
Findings of EACL, 2023 \
[[Paper](https://arxiv.org/pdf/2301.10896.pdf)][[Code+Data](https://github.com/zharry29/causal_reasoning_of_entities_and_events)]

**MCoNaLa: A Benchmark for Code Generation from Multiple Natural Languages**\
Zhiruo Wang\* , Grace Cuenca\*, **Shuyan Zhou^**, Frank F. Xu, Graham Neubig \
Findings of EACL, 2023 \
[[Paper](https://arxiv.org/pdf/2203.08388.pdf)] [[Code+Data](https://github.com/zorazrw/multilingual-conala)]

**Bridging the gap: A Survey on Integrating (Human) Feedback for Natural Language Generation** \
Patrick Fernandes, Aman Madaan, Emmy Liu, António Farinhas, Pedro Henrique Martins, Amanda Bertsch, José GC de Souza, **Shuyan Zhou**, Tongshuang Wu, Graham Neubig, André FT Martins \
TACL, 2023 \
[[Paper](https://browse.arxiv.org/pdf/2305.00955.pdf)]


**Language Models of Code are Few-Shot Commonsense Learners** \
Aman Madaan, **Shuyan Zhou**, Uri Alon, Yiming Yang, Graham Neubig \
EMNLP, 2022 \
[[Paper](https://arxiv.org/pdf/2210.07128.pdf)] [[Code](https://github.com/madaan/CoCoGen)]

**Show Me More Details: Discovering Hierarchies of Procedures from Semi-structured Web Data**\
**Shuyan Zhou**\*, Li Zhang\*, Yue Yang, Qing Lyu, Pengcheng Yin, Chris Callison-Burch, Graham Neubig \
ACL, 2022 \
[[Paper](https://arxiv.org/pdf/2203.07264.pdf)] [[Code+Data](https://github.com/shuyanzhou/wikihow_hierarchy)] [[Demo](https://wikihow-hierarchy.github.io)]


**Procedures as Programs: Hierarchical Control of Situated Agents through Natural Language** \
**Shuyan Zhou**, Pengcheng Yin, Graham Neubig \
Structured and Unstructured Knowledge Integration Workshop at NAACL, 2022\
[[Paper](https://arxiv.org/pdf/2109.08214.pdf)]

**Soft Gazetteers for Low-Resource Named Entity Recognition** \
Shruti Rijhwani, **Shuyan Zhou**, Graham Neubig, Jaime Carbonell \
ACL, 2020\
[[Paper](https://aclanthology.org/2020.acl-main.722.pdf)] [[Code+Data](https://github.com/shrutirij/soft-gazetteers)]


**Improving Candidate Generation for Low-resource Cross-lingual Entity Linking**\
**Shuyan Zhou**, Shruti Rijhwani, John Wieting, Jaime Carbonell, Graham Neubig \
TACL, 2020\
[[Paper](https://aclanthology.org/2020.tacl-1.8.pdf)] [[Code](https://github.com/shuyanzhou/pbel_plus)]


**Towards Zero-resource Cross-lingual Entity Linking**\
**Shuyan Zhou**, Shruti Rijhwani, Graham Neubig \
Deep Learning for Low-Resource NLP Workshop at EMNLP, 2019\
[[Paper](https://aclanthology.org/D19-61.pdf#page=257)] [[Code](https://github.com/shuyanzhou/burn_xel)]

**Improving Robustness of Neural Machine Translation with Multi-task Learning**\
**Shuyan Zhou**, Xiangkai Zeng, Yingqi Zhou, Antonios Anastasopoulos, Graham Neubig \
Conference on Machine Translation (WMT), 2019\
[[Paper](https://aclanthology.org/W19-5368.pdf)] [[Code](https://github.com/shuyanzhou/multitask_transformer)]

**Aggregated Semantic Matching for Short Text Entity Linking**\
Feng Nie, **Shuyan Zhou**, Jing Liu, Jinpeng Wang, Chin-Yew Lin, Rong Pan \
CoNLL, 2018\
[[Paper](https://aclanthology.org/K18-1046.pdf)]

------------

## Academic Service

* **Mentoring**
  * CMU Language Technologies Mentoring Program (for new graduate students; 2021)
  * CMU Graduate Application Support Organizer & Mentor (2020, 2021)
  * CMU AI Mentoring Program (for undergraduates from underrepresented groups; 2020, 2021)

* **Reviewing**
  * ARR 2022, AAAI 2022, ARR 2021, EACL 2021

------------

## Teaching
* TA of CMU 11711 Advanced NLP, Fall 201
* TA of CMU 11747 Neural Network for Natural Language Processing, Spring 2021

------------

## Experience
Master → Ph.D. of Language Technologies, Carnegie Mellon University \
2018.08 - Present \
Advisor: [Graham Neubig](http://phontron.com)

Ph.D. Resident, X, the moonshot factory \
2022.05 - 2022.08 \
Host: [Alex Polozov](https://alexpolozov.com/)

Research Intern, Microsoft \
2020.05 - 2020.08 \
Host: [Kaushik Chakrabarti](https://www.microsoft.com/en-us/research/people/kaushik/) 

B.Eng of Computer Science and Technology, Harbin Institute of Technology \
2014.09 - 2018.06 

Research Intern, Microsoft Research Asia \
2017.07 - 2018.06 \
Host: [Chin-Yew Lin](https://www.microsoft.com/en-us/research/people/cyl/)
