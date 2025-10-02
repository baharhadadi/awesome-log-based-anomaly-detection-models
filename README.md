# Awesome Log-based Anomaly Detection[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Log-based anomaly detection is a critical area of research and practice for ensuring the reliability and security of complex systems. With the increasing volume and complexity of log data, a wide variety of techniques have emerged, ranging from traditional machine learning and statistical models to deep learning and large language model (LLM)-based solutions.

This repository aims to curate a comprehensive collection of resources to support beginners and researchers interested in log-based anomaly detection. Contributions and suggestions are welcome. If you spot any missing resources or wish to contribute, feel free to open an issue or pull request. For questions or suggestions, contact: fhada072@uottawa.ca

---

<font size=5><center><b> Table of Contents </b></center></font>
- [Awesome Libraries and Frameworks](#awesome-libraries-and-frameworks)
- [Awesome Datasets](#awesome-datasets)
- [Awesome Tutorials and Tools](#awesome-tutorials-and-tools)
- [Awesome Papers](#awesome-papers)
  - [Survey and Overview Papers](#survey-and-overview-papers)
  - [Deep Learning Approaches](#deep-learning-approaches)
  - [Language Model-based Methods](#language-model-based-methods)
- [Other Awesome Resources](#other-awesome-resources)

---

## Awesome Libraries and Frameworks
- ![GitHub Repo stars](https://img.shields.io/github/stars/logpai/loglizer?style=social) [LogPAI/Loglizer](https://github.com/logpai/loglizer): A toolkit for automated log analysis using traditional ML and statistical approaches.
- ![GitHub Repo stars](https://img.shields.io/github/stars/logpai/deep-loglizer?style=social) [LogPAI/LogDeep](https://github.com/logpai/deep-loglizer): Deep learning-based framework for log anomaly detection.
- ![GitHub Repo stars](https://img.shields.io/github/stars/LogIntelligence/LogADEmpirical?style=social) [LogADEmpirical](https://github.com/LogIntelligence/LogADEmpirical): Implements deep learning models for sequential log anomaly detection

## Awesome Datasets
- ![GitHub Repo stars](https://img.shields.io/github/stars/logpai/loghub?style=social) [HDFS](https://github.com/logpai/loghub): Hadoop logs for anomaly detection.
- ![GitHub Repo stars](https://img.shields.io/github/stars/logpai/loghub?style=social) [BGL](https://github.com/logpai/loghub): BlueGene/L supercomputer logs.
- ![GitHub Repo stars](https://img.shields.io/github/stars/logpai/loghub?style=social) [Thunderbird, Spirit, and Linux Logs](https://github.com/logpai/loghub): Multiple open-source datasets provided by LogHub.
- [ADFA-LD](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-IDS-Datasets/): Synthetic intrusion detection dataset with system call traces.

## Awesome Tutorials and Tools
- ![GitHub Repo stars](https://img.shields.io/github/stars/IBM/drain3?style=social) [Drain3](https://github.com/IBM/drain3): A Python implementation of the Drain log parsing algorithm with online capabilities.
- ![GitHub Repo stars](https://img.shields.io/github/stars/logpai/logparser?style=social) [LogParse](https://github.com/logpai/logparser): A benchmark of various log parsers.
  
## Awesome Papers

### Survey and Overview Papers
- "Log-based Anomaly Detection with Deep Learning: How Far Are We?" – Le and Zhang, 2022. [Link](https://doi.org/10.1145/3510003.3510155)
- "Deep Learning or Classical Machine Learning? An Empirical Study on Log-Based Anomaly Detection" – Yu el al., 2024. [Link](https://doi.org/10.1145/3597503.36233)
- "A Critical Review of Common Log Data Sets Used for Evaluation of Sequence-based Anomaly Detection Techniques" – Landauer et al., 2024. [Link](https://doi.org/10.1145/3660768)  
- "A comprehensive study of machine learning techniques for log-based anomaly detection" – Ali et al., 2025. [Link](https://doi.org/10.1007/s10664-025-10669-3)

### Traditional Machine Learning Approaches
- "Failure Diagnosis Using Decision Trees" – Chen et al., ICAC 2004. [Link](http://www.cs.berkeley.edu/~brewer/papers/icac2004_chen_diagnosis.pdf)  
- "Failure Prediction in IBM BlueGene/L Event Logs" – Liang et al., ICDM 2007. [Link](https://www.researchgate.net/publication/4324148_Failure_Prediction_in_IBM_BlueGeneL_Event_Logs)  
- "Isolation Forest" – Liu et al., ICDM 2008. [Link](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf)  
- "Large-Scale System Problems Detection by Mining Console Logs" – Xu et al., SOSP 2009. [Link](http://iiis.tsinghua.edu.cn/~weixu/files/sosp09.pdf)  
- "Fingerprinting the Datacenter: Automated Classification of Performance Crises" – Bodík et al., EuroSys 2010. [Link](https://www.microsoft.com/en-us/research/wp-content/uploads/2009/07/hiLighter.pdf)  
- "Mining Invariants from Console Logs for System Problem Detection" – Lou et al., ATC 2010. [Link](https://www.usenix.org/legacy/event/atc10/tech/full_papers/Lou.pdf)  
- "Log Clustering based Problem Identification for Online Service Systems" – Lin et al., ICSE 2016. [Link](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/07/ICSE-2016-2-Log-Clustering-based-Problem-Identification-for-Online-Service-Systems.pdf)  

  
### Deep Learning Approaches
- "DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning" – Du et al., 2017. [Link](https://doi.org/10.1145/3133956.3134015)
- "Detecting Anomaly in Big Data System Logs Using Convolutional Neural Network" – Lu et al., 2018. [Link](https://doi.org/10.1109/DASC/PiCom/DataCom/CyberSciTec.2018.00037)
- "LogAnomaly: Unsupervised Detection of Anomalies in Unstructured Logs" – Meng et al., 2019. [Link](https://doi.org/10.24963/ijcai.2019/658)
- "Robust Log-Based Anomaly Detection on Unstable Log Data" – Zhang et al., 2019. [Link](https://dl.acm.org/doi/10.1145/3338906.3338931)
- "HitAnomaly: Hierarchical Transformers for Anomaly Detection in System Log" –  Huang et al., 2020. [Link](https://doi.org/10.1109/TNSM.2020.3034647)
- "SwissLog: Robust and Unified Deep Learning Based Log Anomaly Detection for Diverse Faults" –  Li et al., 2021. [Link](https://doi.org/10.1109/ISSRE5003.2020.00018)
- "Semi-supervised Log-based Anomaly Detection via Probabilistic Label Estimation" –  Yang et al., 2021. [Link](https://doi.org/10.1109/ICSE43902.2021.00130)
- "Log-based Anomaly Detection Without Log Parsing" – Le and Zhang et al., 2022. [Link](https://doi.org/10.1109/ASE51524.2021.9678773)
- "EvLog: Identifying Anomalous Logs over Software Evolution" – Huo et al., 2023. [Link](https://arxiv.org/abs/2306.01509)

### Language Model-based Methods
- "LogBERT: Log Anomaly Detection via BERT" – Guo et al., 2021. [Link](https://arxiv.org/abs/2103.04475)
- "Interpretable Online Log Analysis Using Large Language Models with Prompt Strategies" – Liu et al., 2024. [Link](https://doi.org/10.1145/3643916.3644408)
- "LLM meets ML: Data-efficient Anomaly Detection on Unstable Logs" – Hadadi et al., 2025. [Link](https://arxiv.org/pdf/2406.07467)

## Other Awesome Resources
- [LogPAI Project](https://www.logpai.com/): A central hub for tools and datasets in log analysis.
- [Kaggle Log Datasets](https://www.kaggle.com/datasets): Several security- and system-related logs.

## Citation
If you find this repository helpful for your research or teaching, please consider citing it:

```bibtex
@misc{awesomelogad,
  title = {Awesome Log-based Anomaly Detection Models},
  author = {Fatemeh Hadadi},
  year = {2025},
  url = {https://github.com/yourusername/awesome-log-anomaly-detection},
  note = {Accessed: YYYY-MM-DD}
}
```

Feel free to fork and contribute!


