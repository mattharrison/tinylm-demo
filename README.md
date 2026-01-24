# tinylm 



[![Coverage badge](https://raw.githubusercontent.com/mattharrison/tinylm-demo/python-coverage-comment-action-data/badge.svg)](https://htmlpreview.github.io/?https://github.com/mattharrison/tinylm-demo/blob/python-coverage-comment-action-data/htmlcov/index.html)


## Usage

This code presents a tiny language model, `Markov`, that can be used to generate
character-level text based on an input corpus. It also includes `WordMarkov`, which
operates at the word level. Both models use a Markov chain approach to generate text.

```python
>>> from tinylm import Markov, WordMarkov
>>> text = "hello world"
>>> markov = Markov(text)
>>> markov.predict("h")
'e'
>>> word_markov = WordMarkov(text)
>>> word_markov.predict("hello")
'world'

```


This project exists to demonstrate features from the [Effective Testing](https://store.metasnake.com/testing).


