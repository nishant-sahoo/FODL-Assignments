# CS6910: Fundamentals of Deep Learning - Programming Assignment II

## Overview
This repository contains the programming assignment for the January-May 2024 semester of the CS6910 course. The assignment focuses on deep learning tasks involving image classification, image captioning, and machine translation.

## Datasets
1. **Image Dataset for Classification**: Used for tasks involving image classification.
2. **Image Captioning Dataset**: Contains images with English captions for image captioning tasks.
3. **Machine Translation Dataset**: Consists of pairs for translation from English to an Indian language.

## Tasks
- **Task 1**: Image classification using a Multi-Layer Feed-Forward Neural Network (MLFFNN) with two hidden layers and Deep CNN features.
  - (a) VGGNet as Deep CNN
  - (b) GoogLeNet as Deep CNN
- **Task 2**: Image classification using a Convolutional Neural Network (CNN) with specific layer configurations and hyperparameters.
- **Task 3**: Image captioning using a CNN with NetVLAD as the encoder and an RNN-based decoder.
- **Task 4**: Image captioning with a CNN encoder and an LSTM-based decoder.
- **Task 5**: Machine translation using an LSTM network for both the encoder and decoder.

## Word Representations
- **English**: GloVe representation
- **Indian Languages**: IndicBERT representation

## Performance Metrics
- The performance is evaluated using BLEU@k scores with k = 1, 2, 3, and 4.
