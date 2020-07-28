<div align="center">
  <img src="https://www.tensorflow.org/images/tf_logo_social.png">
</div>

[![Python](https://img.shields.io/pypi/pyversions/tensorflow.svg?style=plastic)](https://badge.fury.io/py/tensorflow)
[![PyPI](https://badge.fury.io/py/tensorflow.svg)](https://badge.fury.io/py/tensorflow)


**`Documentation`** |
------------------- |
[![Documentation](https://img.shields.io/badge/api-reference-blue.svg)](https://www.tensorflow.org/api_docs/) |

[TensorFlow](https://www.tensorflow.org/) is an end-to-end open source platform
for machine learning. It has a comprehensive, flexible ecosystem of
[tools](https://www.tensorflow.org/resources/tools),
[libraries](https://www.tensorflow.org/resources/libraries-extensions), and
[community](https://www.tensorflow.org/community) resources that lets
researchers push the state-of-the-art in ML and developers easily build and
deploy ML-powered applications.

TensorFlow was originally developed by researchers and engineers working on the
Google Brain team within Google's Machine Intelligence Research organization to
conduct machine learning and deep neural networks research. The system is
general enough to be applicable in a wide variety of other domains, as well.

TensorFlow provides stable [Python](https://www.tensorflow.org/api_docs/python) API.

## Chatbot 

Chatbot answers questions about themselves and FAQs for an online clothing store. It is trained on the data contained in the goal.json file which represents the data dictionary.

**Bag-of-Words model** was used in order to create a vocabulary of unique words that are in the training set of the program. "Stemming" text normalization technique is used for text and word processing. 

**TFlearn library** is used to create the model. A neural network was created with two hidden layers-an input layer and an output layer. Each layer has two neural networks. Their goal is to connect the "bag of words"  with a "tag" in the JSON file. 
The model is trained using the **DNN model class**.

 **Model testing** 

 A model takes a user's input, turns it into a "bag of words", gets model predictions, returns an index of the most probable class and selects an answer from that class.


## Run a project

1. virtualenv env
2. pip install -r requirements.txt
3. python manage.py runserver

Executing *python manage.py runsrver* command, five more files are created: checkpoint, data.pickle, model.tflearn.meta, model.tflearn.index and model.tflearn.data.


