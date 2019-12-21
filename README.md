# rqe-mediqa2019
Recognizing Question Entailment (RQE) in Medical Question Answering (DataSource: MEDIQA 2019)


## Results

| **Model** | **Train Accuracy (%)** | **Validation Accuracy (%)** | **Test Accuracy (%)** |
| --- | --- | --- | --- |
| RoBERTa (pretrained on MNLI) | - | - | **0.626** |
| Fuzzy string matching + Naive Bayes | 0.980  | 0.656 | 0.534 |
| MLP w/ SciBERT | 0.993 | **0.794** | 0.517 |
| Rules-based model | 0.958  | 0.755 | 0.496  |
| BERT + 15% tokens masked | 0.987 | 0.705 | 0.491 |
| BERT | 0.995 | 0.728 | 0.487 |
| LSTM | **0.999** | 0.443 | 0.482 |
