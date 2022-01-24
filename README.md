# English Idiom Classification

Idioms contribute greatly to why natural languages are semantically ambiguous. This is why identifying idiomatic meaning in n-grams is an important NLP task in applications such as, for example, sentiment analysis and machine translation. In my [Russian learning app](https://github.com/markdecl/russian-learning-app), I solved this problem by keeping a bank of known idiomatic phrases in Russian. However, I was curious to find a way to generalise idiom classification using deep learning, so I attempted it in this project - this time on an English dataset.j

## Tools and technologies used:
* Python3
  * BeautifulSoup
  * NumPy
  * pandas
  * NLTK
  * SpaCy
  * scikit-learn
  * keras

## Challenges:
* Preventing overfitting with the training dataset
  * Because of the wide variety of types of idiomatic expressions, it was difficult to prevent the LSTM model overfitting to particular patterns founding the training set, eg. part-of-speech sequences such as noun-preposition-noun

## Credits:
* [_Idiom Token Classification using Sentential Distributed Semantics_](https://aclanthology.org/P16-1019.pdf)
