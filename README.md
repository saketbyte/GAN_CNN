# GAN_CNN
Implementation of 2 Neural Networks, working adversarial to extend the dataset they are trained on. Here: Anime faces for example. The focus is on the implementation and tackling the problems faced during GAN training.


## Description

The above project is an implementation of Generative Adversarial Networks approach as mentioned by sir Ian Goodfellow in his famous paper on GAN, which has also been attached in the repo. The project is a combbination of 2 models both, CNN. One of which is a classifier and the other one is a data generator. For simplicity and saving time, I could train it on a dataset containing Anime faces of different characters, and the model generates new unseen faces of the same. 
The model architecture is versatile, a couple of tweaks here and there when added can help us to train it on a more practically useful data extension.

## Results:

The following GIF shows development over the 25 iterations of GAN model:
![GIF](https://github.com/saketbyte/GAN_CNN/blob/main/gans_training.gif)

### Dependencies
* pytorch - torch.nn is used extensively.
* Python
* CUDA
* OS module


## Acknowledgments

* [Original Paper](https://arxiv.org/abs/1406.2661)
* [Referred documentation of PyTorch](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html)
* [Helpful blog](https://towardsdatascience.com/10-lessons-i-learned-training-generative-adversarial-networks-gans-for-a-year-c9071159628)
