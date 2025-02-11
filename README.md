# Image-Caption-Generator

Hello There!

# Contents
[Go to Introduction] (#introduction)

## Introduction

Image caption generation is a field in artificial intelligence (AI) and computer vision that has been gaining a lot of traction in the past few years. The study of this field has also advanced, with neural network architecture models giving state of the art results. These models usually consist of an encoder-decoder architecture of a convolutional neural network as the encoder for the images and a recurrent neural network (RNN) as the decoder to generate the captions. In this project, we aimed to create a model that can predict captions that are semantically and syntactically accurate with respect to the context of the images. This study used a VGG16 (visual geometry group), a popular pre-trained convolutional neural network (CNN), as encoder for extracting features from the images. This encoder was combined with three different decoder architectures namely long short term memory (LSTM), bidirectional long short term memory and bidirectional long short term memory with attention. Experimental results on the Flicker8k indicated the superiority of the model that used Bidirectional Long Shot Memory (BiLSTM) and attention as decoder in terms of the calculated BLEU1 score of 0.5472, high overall Rouge value as well as the quality of caption generated where it was noticed that this model was able to detect more objects from the image and include it in the caption. Nevertheless, all the other trained models were also able to generate complete, clear, coherent and syntactically correct captions. For the prediction of caption, the methods of greedy search and beam search were explored and experimented.

# Dataset

https://www.kaggle.com/datasets/dibyansudiptiman/flickr-8k


