# Audio Genre Classification

This project focuses on classifying audio files into different music genres using deep learning models. It uses audio processing techniques and convolutional neural networks (CNNs) to analyze audio spectrograms and predict the genre of a given audio track.

## Table of Contents

- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)
- [Contributing](#contributing)

## Dataset

The dataset used in this project consists of audio tracks categorized into various music genres. It can be found in the `/input/gtzan-genre-collection/` directory. The genres include blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, and rock.

## Usage
The code includes three different deep learning models: LSTM, GRU, and CNN, for audio genre classification.
Audio data is processed into spectrograms, which are then used as input features for the models.
The models are trained on a subset of the dataset and evaluated on a validation set.
Model performance metrics, such as accuracy, are provided.


## Results
The ensembled model achieved an accuracy of 77.2% on the validation set. Further optimizations and fine-tuning can potentially improve model performance.

## Dependencies
Python (>=3.6)
TensorFlow (>=2.0)
Librosa
Matplotlib
scikit-learn
PIL

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them with clear, concise commit messages.
Push your branch to your fork.
Open a pull request to the master branch of this repository.
You can find my work at the attached link https://www.kaggle.com/code/kancherlavenkat/music-genre-classification-using-cnn-lstm-gru