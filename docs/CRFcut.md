# CRFcut
## v1.0
**Model Details**

- Developer: Chonlapat Patanajirasit
- Model date: 2020-05-09
- Model version: 1.0
- Used in PyThaiNLP version: 2.2 +
- Filename: `pythainlp/corpus/sentenceseg_crfcut.model`
- GitHub: [https://github.com/vistec-AI/crfcut](https://github.com/vistec-AI/crfcut)
- CRF Model
- License: CC0

**Intended Use**
- Segmenting Thai text into sentences.

**Factors**
- Based on known problems with thai natural Language processing.

**Metrics**
- Evaluation metrics include precision, recall and f1-score.

**Training Data**
Ted + Orchid + Fake review

**Evaluation Data**

Ted + Orchid + Fake review dataset validate

**Quantitative Analyses**

The result of CRF-Cut is trained by different datasets are as follows:

| dataset-train              | dataset-validate | I-precision | I-recall | I-fscore | E-precision | E-recall | E-fscore | space-correct |
|----------------------------|------------------|-------------|----------|----------|-------------|----------|----------|---------------|
| Ted                        | Ted              | 0.99        | 0.99     | 0.99     | 0.74        | 0.70     | 0.72     | 0.82          |
| Ted                        | Orchid           | 0.95        | 0.99     | 0.97     | 0.73        | 0.24     | 0.36     | 0.73          |
| Ted                        | Fake review      | 0.98        | 0.99     | 0.98     | 0.86        | 0.70     | 0.77     | 0.78          |
| Orchid                     | Ted              | 0.98        | 0.98     | 0.98     | 0.56        | 0.59     | 0.58     | 0.71          |
| Orchid                     | Orchid           | 0.98        | 0.99     | 0.99     | 0.85        | 0.71     | 0.77     | 0.87          |
| Orchid                     | Fake review      | 0.97        | 0.99     | 0.98     | 0.77        | 0.63     | 0.69     | 0.70          |
| Fake review                | Ted              | 0.99        | 0.95     | 0.97     | 0.42        | 0.85     | 0.56     | 0.56          |
| Fake review                | Orchid           | 0.97        | 0.96     | 0.96     | 0.48        | 0.59     | 0.53     | 0.67          |
| Fake review                | Fake review      | 1           | 1        | 1        | 0.98        | 0.96     | 0.97     | 0.97          |
| Ted + Orchid + Fake review | Ted              | 0.99        | 0.98     | 0.99     | 0.66        | 0.77     | 0.71     | 0.78          |
| Ted + Orchid + Fake review | Orchid           | 0.98        | 0.98     | 0.98     | 0.73        | 0.66     | 0.69     | 0.82          |
| Ted + Orchid + Fake review | Fake review      | 1           | 1        | 1        | 0.98        | 0.95     | 0.96     | 0.96          |


**Ethical Considerations**

no ideas

**Caveats and Recommendations**

- Thai text only
