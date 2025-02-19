# Speaker Recognition Using Deep Learning

This project demonstrates the process of building a speaker recognition system using deep learning techniques. The workflow includes data preparation, feature extraction, model training, and evaluation.

## Approach

### Data Preprocessing

1. **Dataset Building**: Audio files are organized into speaker and non-speaker categories. Files are copied and renamed accordingly.1. **Dataset Building**: Audio files are organized into speaker and non-speaker categories. Files are copied and renamed accordingly.
2. **Feature Extraction**: MFCC (Mel-frequency cepstral coefficients) features are extracted from the audio files and normalized. These features are used as input to the neural network.ure Extraction\*\*: MFCC (Mel-frequency cepstral coefficients) features are extracted from the audio files and normalized. These features are used as input to the neural network.

### Model Architectureure

1. **Model Setup**: The data is split into training, validation, and test sets. Labels are encoded, and the data is prepared for model training.l Setup\*\*: The data is split into training, validation, and test sets. Labels are encoded, and the data is prepared for model training.
2. **Training**: An LSTM-based neural network model is defined and trained. Early stopping is used to prevent overfitting.\*\*: An LSTM-based neural network model is defined and trained. Early stopping is used to prevent overfitting.

### Evaluation

1. **Model Evaluation**: The model is evaluated on the test set, and results are visualized using a confusion matrix. Accuracy and F1 score are calculated.\*99.87\*: The model is evaluated on the test set, and results are visualized using a confusion matrix. Accuracy and F1 score are calculated.

### Model Saving and Prediction

1. **Model Saving**: The trained model is saved to a file.
2. **Prediction**: A function is defined to preprocess new audio files and predict their class using the trained model.function is defined to preprocess new audio files and predict their class using the trained model.

### Conclusion Conclusion

The project demonstrates the complete workflow for building a speaker recognition system using deep learning, achieving high accuracy and enabling classification of new audio files into speaker and non-speaker categories.The notebook demonstrates the complete workflow for building a speaker recognition system using deep learning, achieving high accuracy and enabling classification of new audio files into speaker and non-speaker categories.
