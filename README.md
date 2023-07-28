# Anomaly Detection in Human Brain via Inductive Learning on Temporal Multiplex Networks 



#### Authors: [Ali Behrouz](https://abehrouz.github.io/), [Margo Seltzer](https://www.seltzer.com/margo/)
#### [Link to the paper](??) ([Arxiv](?))
#### [Poster]()
#### [Spotlight talk]()





### Abstract
Understanding the human brain is an intriguing goal for neuroscience research.  Due to recent advances in machine learning on graphs, representing the connections of the human brain as a network has become one of the most pervasive analytical paradigms. However, most existing graph machine learning-based methods suffer from a subset of three critical limitations: They are (1) designed for one type of data (e.g., fMRI or sMRI) and one individual subject, limiting their ability to use complementary information provided by different images, (2)  designed in supervised or transductive settings, limiting their generalizability to unseen patterns, (3) blackbox models, designed for classifying brain networks, limiting their ability to reveal underlying patterns that might cause the symptoms of a disease or disorder. To address these limitations, we present ADMIRE, an inductive and unsupervised anomaly detection method for multimodal brain networks that can detect anomalous patterns in the brains of people living with a disease or disorder. It uses two different casual multiplex walks, inter-view and intra-view, to automatically extract and learn temporal network motifs. It then uses an anonymization strategy to hide node and relation type identities, keeping the model inductive. We then propose a simple, tree-based explainable model, ADMIRE++, to explain ADMIRE predictions. Our experiments on Parkinson’s Disease, Attention Deficit Hyperactivity Disorder, and Autism Spectrum Disorder show the efficiency and effectiveness of our approaches in detecting anomalous brain activity.





### Reference

```
@inproceedings{
behrouz2023admire,
title={{ADMIRE}++: Explainable Anomaly Detection in the Human Brain via Inductive Learning on Temporal Multiplex Networks},
author={Ali Behrouz and Margo Seltzer},
booktitle={ICML 3rd Workshop on Interpretable Machine Learning in Healthcare (IMLH) },
year={2023},
url={https://openreview.net/forum?id=t4H8acYudJ}
}
```
