# Predicting-Toxicity-using-GNNs

## Abstract: 

Molecular toxicity screening is a crucial step to ensure patient safety in the drug development process. This paper investigates attention-based graph learning strategies, particularly focusing on the effects of self-supervised learning for predicting molecular toxicity. 

We examine and compare the effectiveness of two attention-based GNNs, the Graph Attention Network (GAT) and a Graph Transformer Variant (GTV), highlighting their roles in enhancing drug discovery and safety evaluation. To evaluate the effects of self-supervised learning, we pre-train on the Pub-Chem10M dataset, then fine-tune on the ClinTox and Tox21 dataset. Our results show a strong effect of pre-training when using the GTV, which improves AUC-ROC by 0.156 and 0.012 and F1 by 0.128 and 0.093 for the ClinTox and Tox21 datasets respectively. On the other hand, for the GAT, self-supervised pre-training seems to have a negative effect decreasing AUC-ROC by 0.110 and 0.122 and F1 by 0.002 and 0.028 for the

ClinTox and Tox21 datasets respectively. Pre-training additionally does not have a significant effect on global accuracy in either classification task. However, the decrease in performance from pre-training on the GAT may be due to computa- tional limitations which limit the number of training steps which we could conduct.


Link to the paper[https://drive.google.com/file/d/16iY5Yt4OG3UZ39qk85ci-eF00G-QF1o0/view?usp=sharing]