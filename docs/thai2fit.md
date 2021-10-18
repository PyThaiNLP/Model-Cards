# thai2fit

## v0.32

**Model Details**

- Developer: Charin Polpanumas
- This report author: Wannaphong Phatthiyaphaibun
- Model date: 2019-06-14
- Model version: 0.32
- Used in PyThaiNLP version: 2.0+
- Filename: `~/pythainlp-data/itos_lstm.pkl` and `~/pythainlp-data/thwiki_model_lstm.pth`
- GitHub: [https://github.com/cstorm125/thai2fit](https://github.com/cstorm125/thai2fit)
- Notebook for training: [https://github.com/cstorm125/thai2fit/blob/96fe40d1a9f270dfe0d3a61d2a93254df4078b0d/thwiki_lm/thwiki_lm.ipynb](https://github.com/cstorm125/thai2fit/blob/96fe40d1a9f270dfe0d3a61d2a93254df4078b0d/thwiki_lm/thwiki_lm.ipynb) 
- Language Model
- License: MIT License

**Intended Use**

Language Modeling for Thai text classification pretrained or more.

**Factors**

Based on known problems with Thai natural Language processing. Language Modeling for many tasks of Natural Language processing. Ep. text classification, text generation, and more. 

**Metrics**

Evaluation metrics include Perplexity.

**Training Data**

Thai Wikipedia Dump last updated February 17, 2019

**Evaluation Data**

Thai Wikipedia Dump by using 40M/200k/200k tokens of train-validation-test split

**Quantitative Analyses**

perplexity is `28.71067` with 60,005 embeddings at 400 dimensions

**Ethical Considerations**

This language model is based on the Thai Wikipedia Dump (include bias from Thai Wikipedia).

**Caveats and Recommendations**

It’s want to have fastai 1.9 for using it or using it from pythainlp.
It supports Thai Language only.
