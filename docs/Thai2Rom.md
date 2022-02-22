# Thai2Rom

Thai romanization using LSTM encoder-decoder model with attention mechanism

## v0.1

**Model Details**

- Developer: Chakri Lowphansirikul
- This report author: Wannaphong Phatthiyaphaibun
- Model date: 2019-08-11
- Model version: 0.1
- Used in PyThaiNLP version: 2.1 +
- Filename: `~/pythainlp-data/thai2rom-pytorch-attn-v0.1.tar`
- GitHub: [https://github.com/PyThaiNLP/pythainlp/pull/246](https://github.com/PyThaiNLP/pythainlp/pull/246)
- Train Notebook: [https://github.com/lalital/thai-romanization/blob/master/notebook/thai_romanize_pytorch_seq2seq_attention.ipynb](https://github.com/lalital/thai-romanization/blob/master/notebook/thai_romanize_pytorch_seq2seq_attention.ipynb)
- LSTM Model
- Dataset: [https://github.com/lalital/thai-romanization/blob/master/dataset/data.new](https://github.com/lalital/thai-romanization/blob/master/dataset/data.new)
- License: CC0

**Intended Use**
- conversion of thai text to the Roman.

**Factors**
- Based on known problems with thai natural Language processing.

**Metrics**
- Evaluation metrics include precision, recall and f1-score.

**Training Data**
Thai2Rom trainset

**Evaluation Data**

Thai2Rom testset

**Quantitative Analyses**

The model was evaluated with 3 metrics including F1-score, Exact match, Exact match at character level on the validation set (20% of the dataset or 129,642 examples).

- F1 (macro-average): 0.987
- Exact match: 0.883
- Exact match (Character-level): 0.949


**Ethical Considerations**

no ideas

**Caveats and Recommendations**

- Thai text only
