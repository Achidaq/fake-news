# About this fork

This is a learning/reference fork of [lutzhamel/fake-news](https://github.com/lutzhamel/fake-news).

At the portfolio review on 2026-09-09, this fork's default branch was identical to upstream. The notebooks, report, experiments, and reported results below belong to the upstream project; they are not presented as new experiments by this fork's maintainer.

## Reading guide

- [Classification notebook](fake_news_classification.ipynb): the upstream computational workflow.
- [Report](report.md): the upstream explanation and results.
- [Vectorizer example](vectorizer-example.ipynb): a smaller text-vectorization example.
- [License](LICENSE): the existing project license.

The environment and reported results have not been reproduced as part of this documentation update.

---

# kdnuggets-fake-news
This is a further development of the kdnuggets article on fake news classification by George McIntyre:

https://www.kdnuggets.com/2017/04/machine-learning-fake-news-accuracy.html

In his article McIntyre approaches document classification from a very classical perspective: applying a vector-model to the corpus and then using a Naive Bayes classifier.  Here we take it into the deep learning realm: we apply a deep convolutional network with a traininable word-embedding layer.

We compare the performances of both approaches.  The notebook [fake_news_classification.ipynb](fake_news_classification.ipynb) contains our computational results. The markdown document [report.md](report.md) reports our results in a
more accessible manner.  The results were also posted at [opendatascience](https://opendatascience.com/deep-learning-finds-fake-news-with-97-accuracy).

