[//]: # (Image References)
[image_outputSample]: ./misc/tv_script_sampleOutput.png

# Simpsons TV Script Generation Recurrent Neural Network
TensorFlow implementation of a recurrent neural network (RNN) trained from scratch to generate tv scripts.
![Sample TV script output from the RNN][image_outputSample]

## Project Information
The included [`dlnd_tv_script_generation.ipynb`](https://github.com/JackBurdick/tv_script_generation_rnn/blob/master/dlnd_tv_script_generation.ipynb) provides a commented walk though of the network generation and evaluation.

## Future Improvements:
1. Train with [more data](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data)
2. Train with other data; [A](https://arxiv.org/pdf/1612.01010.pdf) and [B](https://www.kaggle.com/c/seizure-prediction)

### Notes:
* Project designed by Udacity as part of their [DLND](https://www.udacity.com/course/deep-learning-nanodegree-foundation--nd101)
* I got the idea to initialize the biases from a similar project and then read about it [here](https://cs231n.github.io/neural-networks-2/)