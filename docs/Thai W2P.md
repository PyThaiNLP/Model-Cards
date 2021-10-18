# Thai W2P

**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- This report author: Wannaphong Phatthiyaphaibun
- Model date: 2020-12-29
- Model version: 0.1
- Used in PyThaiNLP version: 2.3+
- GitHub: [https://github.com/PyThaiNLP/pythainlp/pull/511](https://github.com/PyThaiNLP/pythainlp/pull/511)
- License: CC0
- train notebook: [https://github.com/wannaphong/Thai_W2P/blob/main/train.ipynb](https://github.com/wannaphong/Thai_W2P/blob/main/train.ipynb)

**Intended Use**

- Converter thai word to thai phoneme
- Not suitable for other language.

**Factors**

- Based on thai word to thai phoneme problems.

**Metrics**

- Evaluation metrics include phoneme error rate (number error / number phonemes)

**Training Data**

Thai W2P (80%)

**Evaluation Data** 

Thai W2P (20%)

**Quantitative Analyses**

```
epoch: 100
step: 100, loss: 0.03179970383644104
step: 200, loss: 0.04126007482409477
step: 300, loss: 0.01877519115805626
step: 400, loss: 0.03311225399374962
per: 0.0432
per: 0.0419
```

**Ethical Considerations**

thai phoneme based on website (wiktionary, Royal Institute et cetera). It may not be the dialect that you use in everyday life.

**Caveats and Recommendations**

- 1 Thai word only
