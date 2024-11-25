
<p align="left">
<a href=http://turing.ac.uk/aicd><img src="imgs/aicd.png" alt="AICD" width="200"/></a>
</p></br>


# Awesome Automated Vulnerability Detection 


Welcome to the Automated vulnerability detection (AVD) repo, maintained by the [AI for Cyber Defence Research Center](https://turing.ac.uk/aicd) at the [Alan Turing Institute](https://turing.ac.uk).
Automated vulnerability detection (AVD) is an emerging research field aiming to automatically detect security vulnerabilities in software without human intervention.
Compared to previous labour-intensive approaches such as code reviews and security audits, accurate AVD solutions enable the scalable detection of vulnerabilities, which facilitates further vulnerability analysis tasks such as exploitation and patching.

The following is a curated list of research papers, datasets, and resources in the field of AVD. 

## Contributions
We aim to keep the list updated to the best of our abilities.
To contribute with new papers and resources, please [open an issue](https://github.com/alan-turing-institute/awesomeAVD/issues/new/choose) or make a PR.

## Table of Contents

 - [Papers](#papers)
 - [Empirical Studies](#empirical-studies)
 - [Surveys](#surveys)
 - [Datasets](#datasets)


## Papers
### 2024
* [Prompt-Enhanced Software Vulnerability Detection Using ChatGPT](https://dl.acm.org/doi/10.1145/3639478.3643065) 
	* code: [\[repo\]](https://github.com/KDEGroup/LLMVulnerabilityDetection)
* [Large Language Model for Vulnerability Detection: Emerging Results and Future Directions](https://dl.acm.org/doi/10.1145/3639476.3639762) 
	* code: [\[repo\]](https://github.com/soarsmu/ChatGPT-VulDetection)
* [GRACE: Empowering LLM-based software vulnerability detection with graph structure and in-context learning](https://dl.acm.org/doi/10.1016/j.jss.2024.112031) 
	* code: [\[repo\]](https://github.com/P-E-Vul/GRACE)
* [Dataflow Analysis-Inspired Deep Learning for Efficient Vulnerability Detection](https://dl.acm.org/doi/10.1145/3597503.3623345) 
	* code: [\[repo\]](https://github.com/ISU-PAAL/DeepDFA)
* [Enhancing vulnerability detection via AST decomposition and neural sub-tree encoding](https://dl.acm.org/doi/10.1016/j.eswa.2023.121865) 
	* code: [\[repo\]](https://github.com/XUPT-SSS/TrVD)
* [Code-centric learning-based just-in-time vulnerability detection](https://dl.acm.org/doi/10.1016/j.jss.2024.112014) 
	* code: [\[repo\]](https://github.com/ttrangnguyen/CodeJIT)
* [LLbezpeky: Leveraging large Language Models for vulnerability detection](https://arxiv.org/abs/2401.01269) 
* [Meta-Path Based Attentional Graph Learning Model for Vulnerability Detection](https://www.computer.org/csdl/journal/ts/2024/03/10376026/1TfBt3jKLtu) 
	* code: [\[repo\]](https://github.com/Xin-Cheng-Wen/MAGNET)
* [Coca: Improving and Explaining Graph Neural Network-Based Vulnerability Detection Systems](https://dl.acm.org/doi/10.1145/3597503.3639168) 
	* code: [\[repo\]](https://github.com/CocaVul/Coca)
* [A vulnerability detection algorithm based on residual graph attention networks for source code imbalance (RGAN)](https://dl.acm.org/doi/10.1016/j.eswa.2023.122216) 

### 2023
* [CSGVD: A deep learning approach combining sequence and graph embedding for source code vulnerability detection](https://dl.acm.org/doi/abs/10.1016/j.jss.2023.111623) 
* [Vulnerability Detection with Graph Simplification and Enhanced Graph Representation Learning](https://dl.acm.org/doi/10.1109/ICSE48619.2023.00191) 
	* code: [\[repo\]](https://github.com/AMPLE001/AMPLE)
* [Vulnerability Detection by Learning From Syntax-Based Execution Paths of Code](https://ieeexplore.ieee.org/document/10153647) 
	* code: [\[repo\]](https://zenodo.org/records/7123322)
* [Transformer-based vulnerability detection in code at EditTime: Zero-shot, few-shot, or fine-tuning?](https://arxiv.org/abs/2306.01754) 
* [DeepVD: Toward Class-Separation Features for Neural Network Vulnerability Detection](https://ieeexplore.ieee.org/abstract/document/10172789) 
	* code: [\[repo\]](https://github.com/deepvd2022/deepvd2022)
* [MFXSS: An effective XSS vulnerability detection method in JavaScript based on multi-feature model](https://dl.acm.org/doi/10.1016/j.cose.2022.103015) 
* [Automated vulnerability detection in source code using quantum natural language processing](https://link.springer.com/chapter/10.1007/978-981-99-0272-9_6) 
* [When Less is Enough: Positive and Unlabeled Learning Model for Vulnerability Detection](https://www.computer.org/csdl/proceedings-article/ase/2023/299600a345/1SBGFjLAP28) 
	* code: [\[repo\]](https://github.com/Eshe0922/PILOT)
* [SedSVD: Statement-level software vulnerability detection based on Relational Graph Convolutional Network with subgraph embedding](https://dl.acm.org/doi/abs/10.1016/j.infsof.2023.107168) 
* [Recurrent Semantic Learning-Driven Fast Binary Vulnerability Detection in Healthcare Cyber Physical Systems](https://ieeexplore.ieee.org/document/9861750) 
* [Cross-domain vulnerability detection using graph embedding and domain adaptation](https://dl.acm.org/doi/10.1016/j.cose.2022.103017) 
* [CPVD: Cross Project Vulnerability Detection Based on Graph Attention Network and Domain Adaptation](https://ieeexplore.ieee.org/document/10149539) 
* [A transformer-based IDE plugin for vulnerability detection](https://dl.acm.org/doi/10.1145/3551349.3559534) 
	* code: [\[repo\]](https://github.com/TQRG/VDET-for-Java)
* [VULDEFF: Vulnerability detection method based on function fingerprints and code differences](https://dl.acm.org/doi/10.1016/j.knosys.2022.110139) 

### 2022
* [VulDeeLocator: A Deep Learning-based Fine-grained Vulnerability Detector](https://www.computer.org/csdl/journal/tq/2022/04/09416836/1t8W1eYcUhy) 
	* code: [\[repo\]](https://github.com/VulDeeLocator/VulDeeLocator)
* [LineVul: a transformer-based line-level vulnerability prediction](https://dl.acm.org/doi/10.1145/3524842.3528452) 
	* code: [\[repo\]](https://github.com/awsm-research/LineVul)
* [LineVD: Statement-level Vulnerability Detection using Graph Neural Networks](https://dl.acm.org/doi/10.1145/3524842.3527949) 
	* code: [\[repo\]](https://github.com/davidhin/linevd)
* [MVD: Memory-Related Vulnerability Detection Based on Flow-Sensitive Graph Neural Networks](https://dl.acm.org/doi/10.1145/3510003.3510219) 
	* code: [\[repo\]](https://github.com/MVDetection/MVD)
* [VulCNN: An Image-inspired Scalable Vulnerability Detection System](https://ieeexplore.ieee.org/document/9793871) 
	* code: [\[repo\]](https://github.com/CGCL-codes/VulCNN)
* [ReGVD: Revisiting Graph Neural Networks for Vulnerability Detection](https://dl.acm.org/doi/10.1145/3510454.3516865) 
	* code: [\[repo\]](https://github.com/daiquocnguyen/GNN-ReGVD)
* [VUDENC: Vulnerability Detection with Deep Learning on a Natural Codebase for Python](https://dl.acm.org/doi/10.1016/j.infsof.2021.106809) 
	* code: [\[repo\]](https://github.com/LauraWartschinski/VulnerabilityDetection)
* [VulBERTa: Simplified Source Code Pre-Training for Vulnerability Detection](https://ieeexplore.ieee.org/document/9892280) 
	* code: [\[repo\]](https://github.com/ICL-ml4csec/VulBERTa)
* [Path-sensitive code embedding via contrastive learning for software vulnerability detection](https://dl.acm.org/doi/10.1145/3533767.3534371) 
* [CD-VulD: Cross-Domain Vulnerability Discovery Based on Deep Domain Adaptation](https://ieeexplore.ieee.org/document/9054952) 
* [VulDeBERT: A Vulnerability Detection System Using BERT](https://ieeexplore.ieee.org/document/9985089) 
	* code: [\[repo\]](https://github.com/SKKU-SecLab/VulDeBERT)
* [Example-based vulnerability detection and repair in Java code](https://dl.acm.org/doi/abs/10.1145/3524610.3527895) 
	* code: [\[repo\]](https://github.com/NiSE-Virginia-Tech/ying-ICPC-2022)
* [Cyber Security Vulnerability Detection Using Natural Language Processing](https://ieeexplore.ieee.org/document/9817336) 
* [VulSlicer: Vulnerability detection through code slicing](https://dl.acm.org/doi/10.1016/j.jss.2022.111450) 
	* code: [\[repo\]](https://zenodo.org/records/6333819)

### 2021
* [Deepwukong: Statically detecting software vulnerabilities using deep graph neural network](https://dl.acm.org/doi/abs/10.1145/3436877) 
	* code: [\[repo\]](https://github.com/jumormt/DeepWukong)
* [Combining Graph-Based Learning With Automated Data Collection for Code Vulnerability Detection](https://ieeexplore.ieee.org/document/9293321) 
	* code: [\[repo\]](https://github.com/HuantWang/FUNDED_NISL)
* [Vulnerability detection with fine-grained interpretations](https://dl.acm.org/doi/abs/10.1145/3468264.3468597) 
	* code: [\[repo\]](https://github.com/vulnerabilitydetection/VulnerabilityDetectionResearch)
* [BGNN4VD: Constructing Bidirectional Graph Neural-Network for Vulnerability Detection](https://dl.acm.org/doi/10.1016/j.infsof.2021.106576) 
* [Software Vulnerability Discovery via Learning Multi-Domain Knowledge Bases](https://ieeexplore.ieee.org/abstract/document/8906156) 
	* code: [\[repo\]](https://github.com/DanielLin1986/RepresentationsLearningFromMulti_domain)
* [Security Vulnerability Detection Using Deep Learning Natural Language Processing](https://ieeexplore.ieee.org/document/9484500) 
* [VDSimilar: Vulnerability detection based on code similarity of vulnerabilities and patches](https://dl.acm.org/doi/10.1016/j.cose.2021.102417) 
* [Vu1SPG: Vulnerability detection based on slice property graph representation learning](https://ieeexplore.ieee.org/document/9700294) 
* [Vulnerability Detection in C/C++ Source Code With Graph Representation Learning](https://ieeexplore.ieee.org/document/9376145) 
* [HAN-BSVD: A hierarchical attention network for binary software vulnerability detection](https://dl.acm.org/doi/abs/10.1016/j.cose.2021.102286) 
* [Software vulnerability detection via deep learning over disaggregated code graph representation](https://arxiv.org/abs/2109.03341) 

### 2020
* [Deep Learning based Vulnerability Detection: Are We There Yet?](https://www.computer.org/csdl/journal/ts/2022/09/09448435/1ugE8leB4Va) 
	* code: [\[repo\]](https://github.com/VulDetProject/ReVeal)
* [LEOPARD: Identifying Vulnerable Code for Vulnerability Assessment through Program Metrics](https://dl.acm.org/doi/10.1109/icse.2019.00024) 
* [DeepBalance: Deep-Learning and Fuzzy Oversampling for Vulnerability Detection](https://ieeexplore.ieee.org/abstract/document/8930093) 
* [MVP: Detecting Vulnerabilities using Patch-Enhanced Vulnerability Signatures](https://dl.acm.org/doi/10.5555/3489212.3489278) 
* [Deep Learning for Software Vulnerabilities Detection Using Code Metrics](https://ieeexplore.ieee.org/document/9069943) 
* [Towards a Deep Learning Model for Vulnerability Detection on Web Application Variants](https://ieeexplore.ieee.org/document/9155596) 
* [A memory-related vulnerability detection approach based on vulnerability features](https://ieeexplore.ieee.org/document/9036137) 

### 2019
* [Devign: Effective Vulnerability Identification by Learning Comprehensive Program Semantics via Graph Neural Networks](https://dl.acm.org/doi/10.5555/3454287.3455202) 
* [muVulDeePecker: A Deep Learning-Based System for Multiclass Vulnerability Detection](https://ieeexplore.ieee.org/abstract/document/8846081) 
* [Static Detection of Control-Flow-Related Vulnerabilities Using Graph Embedding](https://ieeexplore.ieee.org/document/8882745) 
* [Project Achilles: A Prototype Tool for Static Method-Level Vulnerability Detection of Java Source Code Using a Recurrent Neural Network](https://ieeexplore.ieee.org/document/8967427) 
	* code: [\[repo\]](https://gitlab.com/TUSoftwareEngineering/vulnerabilitylocalization-using-machine-learning)
* [A Lightweight Assisted Vulnerability Discovery Method Using Deep Neural Networks](https://ieeexplore.ieee.org/document/8736948) 
	* code: [\[repo\]](https://github.com/Stab1el/LAVDNN)

### 2018
* [VulDeePecker: A Deep Learning-Based System for Vulnerability Detection](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_03A-2_Li_paper.pdf) 
* [Automated Vulnerability Detection in Source Code Using Deep Representation Learning](http://arxiv.org/abs/1807.04320) 
* [SySeVR: A Framework for Using Deep Learning to Detect Software Vulnerabilities](https://www.computer.org/csdl/journal/tq/2022/04/09321538/1qmbsFHMoxi) 
	* code: [\[repo\]](https://github.com/SySeVR/SySeVR)
* [Automated software vulnerability detection with machine learning](https://arxiv.org/pdf/1803.04497) 
* [CryptoGuard: High precision detection of cryptographic vulnerabilities in massive-sized Java projects](https://dl.acm.org/doi/10.1145/3319535.3345659) 
	* code: [\[repo\]](https://github.com/CryptoGuardOSS/cryptoapi-bench)
* [Machine Learning Methods for Software Vulnerability Detection](https://dl.acm.org/doi/abs/10.1145/3180445.3180453) 

### 2017
* [VUDDY: A Scalable Approach for Vulnerable Code Clone Discovery](https://ieeexplore.ieee.org/document/7958600) 
	* code: [\[repo\]](https://github.com/squizz617/vuddy)
* [POSTER: Vulnerability Discovery with Function Representation Learning from Unlabeled Projects](https://dl.acm.org/doi/10.1145/3133956.3138840) 
	* code: [\[repo\]](https://github.com/DanielLin1986/function_representation_learning)
* [Vulnerability detection with deep learning](https://ieeexplore.ieee.org/document/8322752) 
* [Efficient and Flexible Discovery of PHP Application Vulnerabilities](https://ieeexplore.ieee.org/document/7961989) 

### 2016
* [Toward Large-Scale Vulnerability Discovery using Machine Learning](https://dl.acm.org/doi/abs/10.1145/2857705.2857720) 
* [VulPecker: an automated vulnerability detection system based on code similarity analysis](https://dl.acm.org/doi/10.1145/2991079.2991102) 
* [Exploring context-sensitive data flow analysis for early vulnerability detection](https://dl.acm.org/doi/10.1016/j.jss.2015.12.021) 

### 2013
* [Chucky: exposing missing checks in source code for vulnerability discovery](https://dl.acm.org/doi/10.1145/2508859.2516665) 
	* code: [\[repo\]](https://github.com/yangke/chucky-ng/tree/master)

### 2012
* [ReDeBug: Finding Unpatched Code Clones in Entire OS Distributions](https://ieeexplore.ieee.org/document/6234404) 
	* code: [\[repo\]](https://github.com/dbrumley/redebug)

### 2009
* [Inputs of Coma: Static Detection of Denial-of-Service Vulnerabilities](https://ieeexplore.ieee.org/document/5230618) 

### 2008
* [Static detection of cross-site scripting vulnerabilities](https://dl.acm.org/doi/pdf/10.1145/1368088.1368112) 

### 2006
* [Static Detection of Vulnerabilities in x86 Executables](https://ieeexplore.ieee.org/document/4041173) 

## Empirical Studies
### 2024
* [Revisiting the Performance of Deep Learning-Based Vulnerability Detection on Realistic Datasets](https://ieeexplore.ieee.org/document/10587162) 
* [Harnessing large language models for software vulnerability detection: A comprehensive benchmarking study](https://arxiv.org/abs/2405.15614) 
* [Vulnerability Detection with Code Language Models: How Far Are We?](https://www.computer.org/csdl/proceedings-article/icse/2025/056900a469/215aWRJLUZy) 
* [VulEval: Towards repository-level evaluation of software vulnerability detection](https://arxiv.org/abs/2404.15596) 

### 2023
* [Interpreters for GNN-Based Vulnerability Detection: Are We There Yet? - Proceedings of the 32nd ACM SIGSOFT International Symposium on Software Testing and Analysis](https://dl.acm.org/doi/10.1145/3597926.3598145) 
* [ChatGPT for Vulnerability Detection, Classification, and Repair: How Far Are We?](https://ieeexplore.ieee.org/document/10479409) 
* [An Empirical Study of Deep Learning Models for Vulnerability Detection](https://dl.acm.org/doi/10.1109/ICSE48619.2023.00188) 
* [How far have we gone in vulnerability detection using large language models](https://arxiv.org/abs/2311.12420) 
* [Evaluation of ChatGPT model for vulnerability detection](https://arxiv.org/abs/2304.07232) 
* [Understanding the effectiveness of Large Language Models in detecting security vulnerabilities](https://arxiv.org/abs/2311.16169) 

### 2022
* [Transformer-Based Language Models for Software Vulnerability Detection - Proceedings of the 38th Annual Computer Security Applications Conference](https://dl.acm.org/doi/10.1145/3564625.3567985) 
* [An empirical study on the effectiveness of static C code analyzers for vulnerability detection - Proceedings of the 31st ACM SIGSOFT International Symposium on Software Testing and Analysis](https://dl.acm.org/doi/10.1145/3533767.3534380) 

### 2021
* [Explaining Graph Neural Networks for Vulnerability Discovery - Proceedings of the 14th ACM Workshop on Artificial Intelligence and Security](https://dl.acm.org/doi/10.1145/3474369.3486866) 

### 2020
* [A Comparative Study of Neural Network Techniques for Automatic Software Vulnerability Detection](https://ieeexplore.ieee.org/document/9405265) 
* [A Comparative Study of Static Code Analysis tools for Vulnerability Detection in C/C++ and JAVA Source Code](https://www.sciencedirect.com/science/article/pii/S1877050920312023) 
* [The impact factors on the performance of machine learning-based vulnerability detection: A comparative study](https://www.sciencedirect.com/science/article/pii/S0164121220301229) 

### 2019
* [A Comparative Study of Deep Learning-Based Vulnerability Detection System](https://ieeexplore.ieee.org/document/8769937) 

## Surveys
### 2024
* [Large Language Model for Vulnerability Detection: Emerging Results and Future Directions](https://dl.acm.org/doi/10.1145/3639476.3639762) 
* [Top Score on the Wrong Exam: On Benchmarking in Machine Learning for Vulnerability Detection](https://arxiv.org/abs/2408.12986) 

### 2023
* [Android Source Code Vulnerability Detection: A Systematic Literature Review](https://dl.acm.org/doi/10.1145/3556974) 
* [Open Science in Software Engineering: A Study on Deep Learning-Based Vulnerability Detection](https://ieeexplore.ieee.org/document/9894099) 
* [An Investigation of Quality Issues in Vulnerability Detection Datasets](https://ieeexplore.ieee.org/document/10190636) 
* [A survey on automated software vulnerability detection using Machine Learning and Deep Learning](https://arxiv.org/abs/2306.11673) 
* [Benchmarking software vulnerability detection techniques: A survey](https://arxiv.org/abs/2303.16362) 

### 2020
* [Software Vulnerability Detection Using Deep Neural Networks: A Survey](https://ieeexplore.ieee.org/document/9108283) 
* [A Survey of Automatic Software Vulnerability Detection, Program Repair, and Defect Prediction Techniques](https://dl.acm.org/doi/abs/10.1155/2020/8858010) 

### 2018
* [The Coming Era of AlphaHacking?: A Survey of Automatic Software Vulnerability Detection, Exploitation and Patching Techniques](https://ieeexplore.ieee.org/document/8411838) 

### 2017
* [Survey of automated vulnerability detection and exploit generation techniques in cyber reasoning systems](https://link.springer.com/chapter/10.1007/978-3-030-01177-2_79) 

### 2016
* [A Survey on Software Fault Localization](https://ieeexplore.ieee.org/document/7390282) 

## Datasets
### 2021
* [Reveal](https://drive.google.com/drive/folders/1KuIYgFcvWUXheDhT--cBALsfy1I4utOy) 
* [Draper](https://osf.io/d45bw/) 
* [D2A](https://developer.ibm.com/exchanges/data/all/d2a/) 
* [CodeXGLUE](https://github.com/microsoft/CodeXGLUE) 

### 2020
* [Big-Vul](https://github.com/ZeoVan/MSR_20_Code_Vulnerability_CSV_Dataset) 

### 2019
* [Devign](https://sites.google.com/view/devign) 
* [\muVulDeePecker](https://github.com/muVulDeePecker/muVulDeePecker) 

### 2018
* [SySeVR](https://github.com/SySeVR/SySeVR/tree/master/Program%20data) 
* [VulDeePecker](https://github.com/CGCL-codes/VulDeePecker) 

 

