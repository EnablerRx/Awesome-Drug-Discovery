# Awesome-Drug-Discovery

## [ACL 2022](https://www.2022.aclweb.org/papers) 
Key words: medical
- **CBLUE: A Chinese Biomedical Language Understanding Evaluation Benchmark.** Ningyu Zhang, Mosha Chen, Zhen Bi, Xiaozhuan Liang, Lei Li, Xin Shang, Kangping Yin, Chuanqi Tan, Jian Xu, Fei Huang, Luo Si, Yuan Ni, Guotong Xie, Zhifang Sui(Peking University), Baobao Chang(Peking University), Hui Zong, Zheng Yuan(Tsinghua University), Linfeng Li, Jun Yan, Hongying ZAN, Kunli Zhang, Buzhou Tang, Qingcai Chen [[paper]](https://arxiv.org/pdf/2106.08087.pdf) [[code]](https://github.com/CBLUEbenchmark/CBLUE) [[tool]](https://tianchi.aliyun.com/dataset/dataDetail?dataId=95414&lang=en-us)
  - **Abstract:** With the development of biomedical language understanding benchmarks, Artificial Intelligence applications are widely used in the medical field. However, most benchmarks are limited to English, which makes it challenging to replicate many of the successes in English for other languages. To facilitate research in this direction, we collect real-world biomedical data and present the **first Chinese Biomedical Language Understanding Evaluation (CBLUE) benchmark: a collection of natural language understanding tasks including named entity recognition, information extraction, clinical diagnosis normalization, and an associated online platform for model evaluation, comparison, and analysis.** To establish evaluation on these tasks, we report empirical results with the current 11 pre-trained Chinese models, and experimental results show that state-of-the-art neural models perform far worse than the human ceiling.
- **Discriminative Marginalized Probabilistic Neural Method for Multi-Document Summarization of Medical Literature.** Gianluca Moro, Luca Ragazzi, Lorenzo Valgimigli, Davide Freddi. [[paper]](https://aclanthology.org/2022.acl-long.15.pdf) [[code]](https://disi-unibo-nlp.github.io/projects/damen)
  - **Abstract:** Although current state-of-the-art Transformer-based solutions succeeded in a wide range for single-document NLP tasks, **they still struggle to address multi-input tasks such as multi-document summarization.** Many solutions truncate the inputs, thus **ignoring potential summary-relevant contents**, which is unacceptable in the **medical domain** where each information can be vital. Others leverage linear model approximations to apply multi-input concatenation, worsening the results because all in- formation is considered, even if it is conflict- ing or noisy with respect to a shared back- ground. Despite the importance and social impact of medicine, there are no ad-hoc solutions for multi-document summarization. For this reason, we **propose a novel discriminative marginalized probabilistic method (DAMEN) trained to discriminate critical information from a cluster of topic-related medical documents and generate a multi-document summary via token probability marginalization.** Results prove we outperform the previous state-of-the-art on a biomedical dataset for multi-document summarization of systematic literature reviews. Moreover, we perform extensive ablation stud- ies to motivate the design choices and prove the importance of each module of our method.
- **KenMeSH: Knowledge-enhanced End-to-end Biomedical Text Labelling.** Xindi Wang, Robert Mercer, Frank Rudzicz [[paper]](https://aclanthology.org/2022.acl-long.210.pdf) [[code]](https://github.com/xdwang0726/kenmesh)
  - Abstract: Currently, Medical Subject Headings (MeSH) are manually assigned to every biomedical article published and subsequently recorded in the PubMed database to facilitate retrieving relevant information. With the rapid growth of the PubMed database, large-scale biomedical document indexing becomes increasingly important. MeSH indexing is a challenging task for machine learning, as it needs to assign multiple labels to each article from an extremely large hierachically organized collection. To address this challenge, we propose KenMeSH, an end-to-end model that combines new text features and a dynamic knowledge-enhanced mask attention that integrates document features with MeSH label hierarchy and journal correlation features to index MeSH terms. Experimental results show the proposed method achieves state-of-the-art performance on a number of measures.
