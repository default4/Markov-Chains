## Overview

This project demonstrates the implementation of a Markov Chains model to generate text using public domain books available from Project Gutenberg. The Markov Chains model utilizes the statistical properties of the input text to generate new text with a similar structure. The model will be trained on a selected book, and after training, it will generate new text based on the learned probabilities.

## Dependencies

* Python 3.x
* requests
* beautifulsoup4
* numpy
* pandas

To install the dependencies, run the following command:

```
pip install requests beautifulsoup4 numpy pandas
```

## Dataset

The dataset for this project is a public domain book obtained from Project Gutenberg (https://www.gutenberg.org/). The dataset will be downloaded directly in the code using the requests library.