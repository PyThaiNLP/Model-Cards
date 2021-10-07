# Part of speech
## orchid perceptron

**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- Model date: 2018-5-15
- Model version: 1.0
- Used in PyThaiNLP version: 1.7 +
- Filename: `pythainlp/corpus/pos_orchid_perceptron.json`
- perceptron model
- License: CC0
- train notebook: https://github.com/PyThaiNLP/pythainlp_notebook/blob/master/postag/train_orchid_postag_pythainlp.ipynb

**Intended Use**

- Part of speech for Thai.
- Not suitable for other language or other domain of orchid corpus.

**Factors**

- Based on known problems with thai natural Language processing.

**Metrics**

- Evaluation metrics include precision, recall and f1-score.

**Training Data**
Orchid Corpus

**Evaluation Data**
Orchid Corpus

**Quantitative Analyses**

No data

**Ethical Considerations**
no ideas

**Caveats and Recommendations**

- Thai word token only


## LST20 perceptron

**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- Model date: 2020-8-11
- Model version: 0.2.3
- Used in PyThaiNLP version: 2.2.5 +
- Filename: `pythainlp/corpus/pos_lst20_perceptron-v0.2.3.json`
- perceptron model
- License: CC0
- train notebook: https://github.com/PyThaiNLP/pythainlp_notebook/blob/master/postag/train_lst20_pythainlp.ipynb

**Intended Use**

- Part of speech for Thai.
- Not suitable for other language or other domain of LST20 corpus.

**Factors**
- Based on known problems with thai natural Language processing.

**Metrics**

- Evaluation metrics include precision, recall and f1-score.

**Training Data**

LST20 Corpus Train set

**Evaluation Data**

LST20 Corpus Test set

**Quantitative Analyses**

```
              precision    recall  f1-score   support

          AJ       0.90      0.87      0.88      4403
          AV       0.88      0.79      0.83      6722
          AX       0.95      0.94      0.95      7556
          CC       0.94      0.97      0.95     17613
          CL       0.87      0.85      0.86      3739
          FX       0.99      0.99      0.99      6918
          IJ       1.00      0.25      0.40         4
          NG       1.00      1.00      1.00      1694
          NN       0.97      0.98      0.98     58568
          NU       0.98      0.98      0.98      6256
          PA       0.88      0.89      0.88       194
          PR       0.88      0.85      0.86      2139
          PS       0.94      0.93      0.94     10886
          PU       1.00      1.00      1.00     37973
          VV       0.95      0.97      0.96     42586
          XX       0.00      0.00      0.00        27

    accuracy                           0.96    207278
   macro avg       0.88      0.83      0.84    207278
weighted avg       0.96      0.96      0.96    207278
```

**Ethical Considerations**
no ideas

**Caveats and Recommendations**

- Thai word token only

[^ Back to top](#index)

## UD_Thai-PUD Part-of-speech
### v0.1

**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- Model date: 2018-4-15
- Model version: 0.1
- Used in PyThaiNLP version: 1.7 - 2.3
- Filename: `pythainlp/corpus/pos_ud_unigram.json` and `pythainlp/corpus/pos_ud_unigram.json`
- unigram model & perceptron model
- License: CC0
- train notebook: https://github.com/PyThaiNLP/pythainlp_notebook/blob/master/postag/train_ud_thai_pud_pythainlp.ipynb

**Intended Use**

- Part of speech for Thai.
- Not suitable for other language or other domain of UD_Thai-PUD corpus.

**Factors**
- Based on known problems with thai natural Language processing.

**Metrics**
None

**Training Data**

UD_Thai-PUD v2.2 https://github.com/UniversalDependencies/UD_Thai-PUD/releases/tag/r2.2

**Evaluation Data**

None

**Quantitative Analyses**
None

**Ethical Considerations**
no ideas

**Caveats and Recommendations**

- Thai word token only


#### v0.2

**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- Model date: 2021-7-31
- Model version: 0.2
- Used in PyThaiNLP version: 2.4 +
- Filename: `pythainlp/corpus/pos_ud_unigram-v0.2.json` and `pythainlp/corpus/pos_ud_unigram-v0.2.json`
- unigram model & perceptron model
- License: CC0
- GitHub: https://github.com/PyThaiNLP/pythainlp/pull/603
- train notebook: https://github.com/PyThaiNLP/pythainlp_notebook/blob/master/postag/train_ud_thai_pud_pythainlp-v0.2.ipynb

**Intended Use**

- Part of speech for Thai.
- Not suitable for other language or other domain of UD_Thai-PUD corpus.

**Factors**
- Based on known problems with thai natural Language processing.

**Metrics**
None

**Training Data**

UD_Thai-PUD v2.8 https://github.com/UniversalDependencies/UD_Thai-PUD/releases/tag/r2.8

**Evaluation Data**

None

**Quantitative Analyses**
None

**Ethical Considerations**
no ideas

**Caveats and Recommendations**

- Thai word token only