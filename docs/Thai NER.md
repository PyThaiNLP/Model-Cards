# Thai NER

## v1.4

**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- Model date: 2020-5-21
- Model version: 1.4
- Used in PyThaiNLP version: 2.2 +
- Filename: `~/pythainlp-data/thai-ner-1-4.crfsuite`
- CRF Model
- License: CC0
- GitHub for Thai NER 1.4 (Data and train notebook): https://github.com/wannaphong/thai-ner/tree/master/model/1.4

**Intended Use**

- Named-Entity Tagging for Thai.
- Not suitable for other language or non-news domain.

**Factors**

- Based on known problems with thai natural Language processing.

**Metrics**

- Evaluation metrics include precision, recall and f1-score.

**Training Data**
ThaiNER 1.3 Corpus Train set

**Evaluation Data**
ThaiNER 1.3 Corpus Test set

**Quantitative Analyses**

```

                precision    recall  f1-score   support

        B-DATE       0.92      0.86      0.89       375
        I-DATE       0.94      0.94      0.94       747
       B-EMAIL       1.00      1.00      1.00         5
       I-EMAIL       1.00      1.00      1.00        28
         B-LAW       0.71      0.56      0.62        43
         I-LAW       0.74      0.70      0.72       154
         B-LEN       0.96      0.93      0.95        29
         I-LEN       0.98      0.94      0.96        69
    B-LOCATION       0.88      0.77      0.82       864
    I-LOCATION       0.86      0.73      0.79       852
       B-MONEY       0.98      0.85      0.91       105
       I-MONEY       0.96      0.95      0.95       239
B-ORGANIZATION       0.90      0.78      0.84      1166
I-ORGANIZATION       0.84      0.77      0.81      1338
     B-PERCENT       1.00      0.97      0.99        34
     I-PERCENT       1.00      0.96      0.98        51
      B-PERSON       0.96      0.82      0.88       676
      I-PERSON       0.94      0.92      0.93      2424
       B-PHONE       1.00      0.72      0.84        29
       I-PHONE       0.96      0.92      0.94        78
        B-TIME       0.87      0.73      0.79       172
        I-TIME       0.94      0.83      0.88       336
         B-URL       0.89      1.00      0.94        24
         I-URL       0.96      1.00      0.98       371
         B-ZIP       1.00      1.00      1.00         4

     micro avg       0.91      0.84      0.87     10213
     macro avg       0.93      0.87      0.89     10213
  weighted avg       0.91      0.84      0.87     10213
   samples avg       0.17      0.17      0.17     10213
```
**Ethical Considerations**
no ideas

**Caveats and Recommendations**

- Thai text only


## v1.5

**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- Model date: 2021-1-16
- Model version: 1.5
- Used in PyThaiNLP version: 2.3 +
- Filename: `~/pythainlp-data/thai-ner-1-5-newmm-lst20.crfsuite`
- CRF Model
- License: CC0
- GitHub for Thai NER 1.5 (Data and train notebook): `thai-ner-1-5-newmm-lst20.ipynb` https://github.com/wannaphong/thai-ner/tree/master/model/1.5

**Intended Use**

- Named-Entity Tagging for Thai.
- Not suitable for other language or non-news domain.

**Factors**

- Based on known problems with thai natural Language processing.

**Metrics**

- Evaluation metrics include precision, recall and f1-score.

**Training Data**

ThaiNER 1.5 Corpus Train set (5089 sent)

**Evaluation Data**

ThaiNER 1.5 Corpus Test set (1274 sent)

**Quantitative Analyses**

```
                precision    recall  f1-score   support

        B-DATE       0.93      0.82      0.87       350
        I-DATE       0.95      0.94      0.95       665
         B-LAW       0.85      0.54      0.66        87
         I-LAW       0.85      0.64      0.73       253
         B-LEN       1.00      0.75      0.86        12
         I-LEN       1.00      0.69      0.82        26
    B-LOCATION       0.81      0.70      0.75       620
    I-LOCATION       0.74      0.72      0.73       533
       B-MONEY       1.00      0.91      0.95       131
       I-MONEY       0.99      0.95      0.97       321
B-ORGANIZATION       0.92      0.70      0.80      1334
I-ORGANIZATION       0.80      0.73      0.76      1198
     B-PERCENT       0.94      0.88      0.91        17
     I-PERCENT       0.91      0.95      0.93        22
      B-PERSON       0.96      0.78      0.86       607
      I-PERSON       0.94      0.88      0.91      2181
       B-PHONE       1.00      0.50      0.67         2
       I-PHONE       1.00      1.00      1.00         8
        B-TIME       0.93      0.66      0.77        87
        I-TIME       0.97      0.77      0.86       158
         B-URL       0.91      0.83      0.87        12
         I-URL       0.93      0.96      0.94        94

     micro avg       0.89      0.79      0.84      8718
     macro avg       0.92      0.79      0.84      8718
  weighted avg       0.90      0.79      0.84      8718
   samples avg       0.16      0.16      0.16      8718
```

**Ethical Considerations**
no ideas

**Caveats and Recommendations**

- Thai text only