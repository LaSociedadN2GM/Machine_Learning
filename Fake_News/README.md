<!--
*** Thanks for checking out this README Template
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<p align="center">
 <h1>F A K E N E W S </h1>
 </p>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [About the Project](#about-the-project)
- [Getting Started](#getting-started)
- [Algorithms](#algorithms)
- [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->

## About The Project

Fake News UTK Machine Learning Club is one of the examples where Long Short Term Memory (LSTM) networks are used, they are very good at learning from past sequences and they improve with each training period in fake news, the feactures were text which are non-numerical values ​​could not apply regression algorithms or others and taking into account that it is necessary to train and remember the features that the fake news has in the text, the application gives us 93% confidence but it can be improved with more training of this, one of the disadvantages was the time these networks take considering the epochs as remember the dimensionality of the vectors are extended.

<!-- GETTING STARTED -->

## Getting Started

You find out this dataset in https://www.kaggle.com/c/fake-news/data

### Prerequisites

- npm

```sh
Sklearn
TensorFlow
NPLTKL
```

![](images/LSTM.png)

<!-- USAGE EXAMPLES -->

<!-- ROADMAP -->

<!-- CONTRIBUTING -->

<!-- LICENSE -->

## algorithms

How work LSTM is complicated to explain .
Recurrents neuronal networks have cycles where information persists
, LTSM networks are not very different All recurrent neural networks are in the form of a chain of repeated neural network modules.
In standard RNNs, this repeating module will have a very simple structure, like a single layer of tanh
The key to LSTM are the states of cells, the horizontal ones with some linear interactions are like reflected mirrors, you do not have the ability to remove or add information, the exit doors pass through layers of sigmoidal function and the outputs of that layer generate numbers between zero or one if he lets or does not let pass

## acknowledgements

http://colah.github.io/posts/2015-08-Understanding-LSTMs/
