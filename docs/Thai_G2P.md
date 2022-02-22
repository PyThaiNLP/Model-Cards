# Thai G2P

Thai Grapheme-to-Phoneme (Thai G2P) based on Deep Learning (Seq2Seq model)

## v0.1

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