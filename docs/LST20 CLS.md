# LST20 CLS
## v0.2
**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- Model date: 2020-10-03
- Model version: 0.2
- Used in PyThaiNLP version: 2.2.4 +
- Filename: `~/pythainlp-data/cls-v0.2.crfsuite`
- GitHub: https://github.com/PyThaiNLP/pythainlp/pull/479
- CRF Model
- License: CC0

**Intended Use**

- Segmenting Thai text into clauses (smaller than a sentence but bigger than a word)
- Not suitable for other language or non-news domain.

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
no ideas

**Caveats and Recommendations**

- The user must perform word segmentation first before using this model.
- Thai text only
