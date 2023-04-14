## Overview

This project demonstrates the implementation of a Markov Chains model to generate text using movie scripts. The Markov Chains model utilizes the statistical properties of the input text to generate new text with a similar structure. The model will be trained on a selected movie script, and after training, it will generate new text based on the learned probabilities.

## Dependencies

* Python 3.x
* requests
* numpy
* pandas

To install the dependencies, run the following command:

```
pip install requests numpy pandas
```

## Dataset

The dataset for this project consists of movie scripts obtained from IMSDb (https://www.imsdb.com/). The dataset will be downloaded directly in the code using the requests library.