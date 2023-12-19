# CLS

## Blackboard CLS
### V1.0
**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- This report author: Wannaphong Phatthiyaphaibun
- Model date: 2022-10-14
- Model version: 1.0
- Used in PyThaiNLP version: 3.2 +
- Filename: `pythainlp/corpus/blackboard-cls_v1.0.crfsuite`
- GitHub: [https://github.com/PyThaiNLP/pythainlp/issues/729](https://github.com/PyThaiNLP/pythainlp/issues/729)
- CRF Model
- License: CC0

**Intended Use**

- Segmenting Thai text into clauses (smaller than a sentence but bigger than a word)
- Not suitable for other language or non-news domains.

**Factors**

- Based on known problems with thai natural Language processing.

**Metrics**

- Evaluation metrics include precision, recall and f1-score.

**Training Data**

Blackboard treebank

**Evaluation Data**

Blackboard treebank

**Quantitative Analyses**

```
              precision    recall  f1-score   support

       B_CLS       1.00      1.00      1.00     91698
       E_CLS       1.00      1.00      1.00     91700
       I_CLS       1.00      1.00      1.00    707795

   micro avg       1.00      1.00      1.00    891193
   macro avg       1.00      1.00      1.00    891193
weighted avg       1.00      1.00      1.00    891193
 samples avg       1.00      1.00      1.00    891193
```
**Ethical Considerations**

- It trains from Blackboard treebank. It is possible to have a bias from Blackboard treebank.

**Caveats and Recommendations**

- The user must perform word segmentation first before using this model.
- Thai text only


## LST20 CLS
### v0.2
**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- This report author: Wannaphong Phatthiyaphaibun
- Model date: 2020-10-03
- Model version: 0.2
- Used in PyThaiNLP version: 2.2.4 +
- Filename: `~/pythainlp-data/cls-v0.2.crfsuite`
- GitHub: [https://github.com/PyThaiNLP/pythainlp/pull/479](https://github.com/PyThaiNLP/pythainlp/pull/479)
- CRF Model
- License: CC0

**Intended Use**

- Segmenting Thai text into clauses (smaller than a sentence but bigger than a word)
- Not suitable for other language or non-news domains.

**Factors**

- Based on known problems with thai natural Language processing.

**Metrics**

- Evaluation metrics include precision, recall and f1-score.

**Training Data**

LST20 Corpus Train set (news domain)

**Evaluation Data**

LST20 Corpus Test set (news domain)

**Quantitative Analyses**

```
              precision    recall  f1-score   support

       B_CLS       0.90      0.94      0.92     16111
       E_CLS       0.90      0.94      0.92     15947
       I_CLS       0.99      0.97      0.98    169565

   micro avg       0.97      0.97      0.97    201623
   macro avg       0.93      0.95      0.94    201623
weighted avg       0.97      0.97      0.97    201623
 samples avg       0.94      0.94      0.94    201623
```
**Ethical Considerations**

- It trains from LST20 Corpus. It is possible to have a bias from LST20 Corpus.

**Caveats and Recommendations**

- The user must perform word segmentation first before using this model.
- Thai text only
