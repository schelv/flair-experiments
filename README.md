# `flair-experiments`

This repository is part of my NLP research with
[`flair`](https://github.com/zalandoresearch/flair), a state-of-the-art NLP
framework from [Zalando Research](https://research.zalando.com/).

This repository will include models for various NLP benchmarks, such as
GermEval 2018. It will be updated frequently. So please star or watch this
repository 😅

# English CoNLL-2003 (NER)

For the integration of PyTorch-Transformers into `flair`, I run experiments
for several Transformer-based architectures.

All details can be found in the [NER English](conll2002-ner-dutch/README.md)
readme.

# Archived

The following experiments are achieved (and needs to be re-run with the
latest version of `flair`).

## GermEval 2018

### Task 1

The first task of GermEval 2018 is to decide whether a tweet includes a) some
form of offensive language or b) or not.

All details for training a model with `flair` and achieving state-of-the-art
results are located in the [GermEval 2018](germeval2018/README.md) readme.

The winning system for task 1 achieved a F-Score of 76.77. The currently best
model trained with `flair` achieves a F-Score from **74.24**.

## Fine-grained POS Tagging of German Tweets

All details for training a model with `flair` and achieving a new
state-of-the-art result for the paper
[Fine-grained POS Tagging of German Tweets](https://pdfs.semanticscholar.org/82c9/90aa15e2e35de8294b4a721785da1ede20d0.pdf)
are located in the [POS Twitter German](pos-twitter-german/README.md) readme.

The paper reported an accuracy of 89.42. The currently best model trained with
`flair` achieves **92.49** (+ 3.07).

## German Universal Dependencies 1.2

All details for training a model with `flair` on German universal dependencies
and achieving a new state-of-the-art result can be found in the
[UD German](ud-german/README.md) readme.

The current state-of-the-art result for German UD is reported by
[Yasunaga et. al (2017)](https://arxiv.org/abs/1711.04903). They use
adversarial training and their system achieves an accuracy of 94.35. With `flair`
an accuracy of **94.52** (+ 0.17) can be achieved.

## Bulgarian Universal Dependencies 1.2

All details for training a model with `flair` on Bulgarian universal
dependencies and achieving a new state-of-the-art result can be found in the
[UD Bulgarian](ud-bulgarian/README.md) readme.

The current state-of-the-art result for Bulgarian UD is reported by
[Yasunaga et. al (2017)](https://arxiv.org/abs/1711.04903). They use
adversarial training and their system achieves an accuracy of 98.53. With `flair`
an accuracy of **99.08** (+ 0.55) can be achieved.

## Slovenian Universal Dependencies 1.2

All details for training a model with `flair` on Slovenian universal
dependencies and achieving a new state-of-the-art result can be found in the
[UD Slovenian](ud-slovenian/README.md) readme.

The current state-of-the-art result for Slovenian UD is reported by
[Yasunaga et. al (2017)](https://arxiv.org/abs/1711.04903). They use
adversarial training and their system achieves an accuracy of 98.11. With `flair`
an accuracy of **98.88** (+ 0.77) can be achieved.

## Dutch Universal Dependencies 1.2

All details for training a model with `flair` on Dutch universal
dependencies and achieving a new state-of-the-art result can be found in the
[UD Dutch](ud-dutch/README.md) readme.

The current state-of-the-art result for Dutch UD is reported by
[Plank et. al (2016)](https://arxiv.org/abs/1711.04903). They use
a bi-lstm architecture and their system achieves an accuracy of 93.82. With `flair`
an accuracy of **93.84** (+ 0.02) can be achieved.

## Dutch Named Entity Recognition (CoNLL 2002)

All details for training a model with `flair` for the CoNLL 2002 Named Entity
Recognition task on Dutch and achieving a state-of-the-art result can be found
in the [NER Dutch](conll2002-ner-dutch/README.md) readme.

The best reporting system in the CoNLL 2002 task achieved a f-score of 77.05.
With `flair` a f-score of **87.91** (+ 10.86) can be achieved.

## Basque Universal Dependencies 1.2

All details for training a model with `flair` on Basque universal
dependencies and achieving a new state-of-the-art result can be found in the
[UD Basque](ud-basque/README.md) readme.

The current state-of-the-art result for Basque UD is reported by
[Plank et. al (2016)](https://arxiv.org/abs/1711.04903). They use
a bi-lstm architecture and their system achieves an accuracy of 95.51. With `flair`
an accuracy of **97.17** (+ 1.66) can be achieved.

# Contact (Bugs, Feedback, Contribution and more)

For questions about `flair-experiments`, just open an issue/pull request.
