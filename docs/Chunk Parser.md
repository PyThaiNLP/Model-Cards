# Chunk Parser

## CRFChunk orchidpp
### v0.2
**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- Model date: 2021-01-21
- Model version: 0.2
- Used in PyThaiNLP version: 2.3
- GitHub:  [https://github.com/PyThaiNLP/pythainlp/pull/524](https://github.com/PyThaiNLP/pythainlp/pull/524)
- License: CC0
- train notebook: [https://github.com/PyThaiNLP/pythainlp_notebook/pull/1](https://github.com/PyThaiNLP/pythainlp_notebook/pull/1)
- Dataset: ORCHID++ from [Thai Treebanks Dataset](https://github.com/tchayintr/thtb). We extract sentence subtree from tree to train data. (5,000 tree up to 5,935 tree)

**Intended Use**

- Parser thai sentence to phrase structure
- Not suitable for other language or other domain of orchid corpus.

**Factors**

- Based on thai chunk parser problems.

**Metrics**

- Evaluation metrics include precision, recall and f1-score.

**Training Data**

ORCHID++ (90%) from [Thai Treebanks Dataset](https://github.com/tchayintr/thtb)

**Evaluation Data** 

ORCHID++ (10%) from [Thai Treebanks Dataset](https://github.com/tchayintr/thtb)

**Quantitative Analyses**


```python
              precision    recall  f1-score   support

        B-NP       0.95      0.98      0.96       518
        I-NP       0.86      0.91      0.88      2128
           O       0.87      0.91      0.89       280
        B-PP       0.91      0.77      0.83        65
        I-PP       0.66      0.52      0.59       252
         B-S       0.65      0.49      0.56        90
         I-S       0.67      0.49      0.56      1082
        B-VP       0.86      0.89      0.88       515
        I-VP       0.90      0.94      0.92      4565

   micro avg       0.86      0.86      0.86      9495
   macro avg       0.81      0.77      0.79      9495
weighted avg       0.86      0.86      0.86      9495
 samples avg       0.86      0.86      0.86      9495

```


**Ethical Considerations**

- It trains from orchid++ corpus. It is possible to have a bias from orchid++ corpus.

**Caveats and Recommendations**

- 1 Thai sentence with `[(word,part-of-speech)]` (part-of-speech model trained from orchid corpus)