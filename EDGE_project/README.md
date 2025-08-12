
# UrbanSound Classification

This repository contains a project on classifying urban sounds using the [UrbanSound8K](https://urbansounddataset.weebly.com/urbansound8k.html) dataset. The dataset consists of 8,732 labeled sound excerpts (≤4s) of urban sounds, categorized into 10 classes.

## Project Overview
The goal of this project is to build and compare different deep learning models for classifying urban sound events. The models implemented include:
- Convolutional Neural Networks (CNNs)
- Recurrent Neural Networks (RNNs)
- Hybrid CNN-RNN models
- Transfer Learning using pretrained architectures

## Dataset
The dataset consists of 10 classes:
- Air Conditioner
- Car Horn
- Children Playing
- Dog Bark
- Drilling
- Engine Idling
- Gunshot
- Jackhammer
- Siren
- Street Music

### Preprocessing
- Converted audio files into Mel-spectrograms
- Normalized the spectrogram images
- Augmented data to improve model generalization

## Models Implemented
1. **CNN Model:** Built from scratch for feature extraction.
2. **RNN Model:** LSTM-based model for capturing temporal dependencies.
3. **CNN + RNN Hybrid:** Combines CNN for feature extraction and RNN for sequential learning.


## Results
| Model | Accuracy |
|--------|------------|
| CNN | 82% |
| RNN (LSTM) | 84% |
| CNN + RNN | 86% |




## Future Improvements
- Implement attention mechanisms
- Experiment with more advanced augmentations
- Optimize hyperparameters

## References
- [UrbanSound8K Dataset](https://urbansounddataset.weebly.com/urbansound8k.html)
- [Librosa Documentation](https://librosa.org/doc/latest/index.html)

## Author
TAYBA BUSRA
