Project was created by Udacity as part of their Deep Learning Nanodegree

Notes:
* I found that increasing the sequence length hyperparameter and decreasing the learning rate improved loss performance dramatically.
* I'd like to try this again but with more data and larger seq. lengths to see when this is no longer true
* I got the idea to initialize the biases from another project and then read about it [here](https://cs231n.github.io/neural-networks-2/)

TODO:
* look through `get_batches()` and modify as needed -- I had trouble with this function
* try with [more data](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data)
* try with other data [A](https://arxiv.org/pdf/1612.01010.pdf) and [B](https://www.kaggle.com/c/seizure-prediction)
* increase seq.len hyperparameter and inspect on tensorboard
* implement a dynamic standard deviation calculation


References:
* [Udacity materials](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101)
  * Foundational materials
  * Material from 'Sentiment Prediction RNN'
* [slack channel](nd101.slack.com)
  * read answers to questions
* Github repos
  * [example 1](https://github.com/Suranjit/dlnd_tv_script_generation/blob/master/dlnd_tv_script_generation.ipynb)
  * [example 2](https://github.com/andrea137/tv-script-generation/blob/master/dlnd_tv_script_generation.ipynb)
    * read for comparison
* [tensor flow documentation](https://www.tensorflow.org/)
  * mostly regarding parameter order/keywords
