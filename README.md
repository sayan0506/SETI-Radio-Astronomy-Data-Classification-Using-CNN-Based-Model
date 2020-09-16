# SETI-Radio-Astronomy-Data-Classification-Using-CNN-Based-Model

Building a Deep CNN model for classifying four different types of radio signals captured through **Allen Telescope** array in **SETI(Search for extraterrestrial intelligence)** institute.

Classifying 4 different types of radio signals from sequential data captured by Allen Telescope array in SETI in csv format, which in turn converted to 2D spectrogram data, where only initial time frame is considered for the classification problem.

In this project mainly 4 following types of radio signals are classified, which are:

>**1. Squiggle**
>
>**2. Narrowband**
>
>**3. Noise**
>
>**4. Narrorbanddrd**

This work is based on a paper ["Machine Vision and Deep Learning for Classification of Radio SETI Signals"](https://arxiv.org/ftp/arxiv/papers/1902/1902.02426.pdf).

The Convolution Neural Network model has been trained from scratch using Tensorflow, Keras as backend. By the end of the training the CNN can be used for classifictaion of that radio astronomy data.

The details of entire data pre-processing, model training and implementation can be found in the python notebook [**code**](https://github.com/sayan0506/SETI-radio-signal-classification-using-CNN-based-model/blob/master/SETI_radio_signal_classification_using_CNN.ipynb). The notebook was implemented in [Google Collab](https://colab.research.google.com/).

The saved model can be found in [Weights](https://github.com/sayan0506/SETI-Radio-Astronomy-Data-Classification-Using-CNN-Based-Model/tree/master/Weights_file).
The parameter file is too large to upload.

* **Resources:**
1.   https://github.com/setiquest/ml4seti
2. ["Machine Vision and Deep Learning for Classification of Radio SETI Signals"](https://arxiv.org/ftp/arxiv/papers/1902/1902.02426.pdf) 

**All the contents are made public, and all modifications, pull requests are welcome but please open issue and discuss before executing any major change in the repository.**
