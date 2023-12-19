# Transliteration
## Thai W2P

**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- This report author: Wannaphong Phatthiyaphaibun
- Model date: 2020-12-29
- Model version: 0.1
- Used in PyThaiNLP version: 2.3+
- Filename: `~/pythainlp-data/w2p_0.1.npy`
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

This corpus is based on the website, such as wiktionary, Royal Institute et cetera and more. It may not be the dialect that you use in everyday life.

**Caveats and Recommendations**

- 1 Thai word only

## Thai2Rom

Thai romanization using LSTM encoder-decoder model with attention mechanism

### v0.1

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

## Thai G2P

Thai Grapheme-to-Phoneme (Thai G2P) based on Deep Learning (Seq2Seq model)

### v0.1

**Model Details**

- Developer: Wannaphong Phatthiyaphaibun
- This report author: Wannaphong Phatthiyaphaibun
- Model date: 2020-08-20
- Model version: 0.1
- Used in PyThaiNLP version: 2.2+
- Filename: `~/pythainlp-data/thaig2p-0.1.tar`
- Pull request GitHub: [https://github.com/PyThaiNLP/pythainlp/pull/377](https://github.com/PyThaiNLP/pythainlp/pull/377)
- GitHub: [https://github.com/wannaphong/thai-g2p](https://github.com/wannaphong/thai-g2p)
- Train notebook: [https://github.com/wannaphong/thai-g2p/blob/master/train.ipynb](https://github.com/wannaphong/thai-g2p/blob/master/train.ipynb)
- Dataset: [wiktionary-11-2-2020.tsv](https://github.com/wannaphong/thai-g2p/blob/master/wiktionary-11-2-2020.tsv)
- Seq2Seq model
- License: CC0

**Intended Use**

Grapheme-to-Phoneme conversion tool.

**Factors**

- Based on thai grapheme-to-phoneme conversion problems.

**Metrics**

f1-score.

**Training Data**

wiktionary trainset

**Evaluation Data**

wiktionary testset

**Quantitative Analyses**

```
F1 (macro-average) =  0.9415941561267093
EM =  0.71
EM (Character-level) =  0.8660247630539959
save best model em score=0.71 at epoch=1148
Save model at epoch  1148
Epoch: 1149 | Time: 2m 55s
	Train Loss: 0.352 | Train PPL:   1.422
	 Val. Loss: 0.512 |  Val. PPL:   1.669
epoch=1149, teacher_forcing_ratio=0.4
```

**Ethical Considerations**

This model is based on the Thai wiktionary Dump (include bias from Thai wiktionary).

**Caveats and Recommendations**

- 1 Thai word only
