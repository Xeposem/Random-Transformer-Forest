Official code repository of our paper, An Ensemble of Pre-trained Transformer Models For Imbalanced Multiclass Malware Classification. 
https://arxiv.org/abs/2112.13236

Abstract:
Classification of malware families is crucial for a comprehensive understanding of how they can infect devices, computers, or systems. Thus, malware identification enables security researchers and incident responders to take precautions against malware and accelerate mitigation. API call sequences made by malware are widely utilized features by machine and deep learning models for malware classification as these sequences represent the behavior of malware. However, traditional machine and deep learning models remain incapable of capturing sequence relationships between API calls. On the other hand, the transformer-based models process sequences as a whole and learn relationships between API calls due to multi-head attention mechanisms and positional embeddings. Our experiments demonstrate that the transformer model with one transformer block layer surpassed the widely used base architecture, LSTM. Moreover, BERT or CANINE, pre-trained transformer models, outperformed in classifying highly imbalanced malware families according to evaluation metrics, F1-score, and AUC score. Furthermore, the proposed bagging-based random transformer forest (RTF), an ensemble of BERT or CANINE, has reached the state-of-the-art evaluation scores on three out of four datasets, particularly state-of-the-art F1-score of 0.6149 on one of the commonly used benchmark dataset.
