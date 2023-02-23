# Emotion Detection using Machine Learning Classification Algorithms, Neural Networks and Keras
This project demonstrates the use of machine learning classification algorithms and neural networks for emotion detection in textual data. The project uses Keras, an open-source deep learning framework written in Python, for building and training the neural network.

## Dataset
The dataset used in this project is the ISEAR dataset, which contains 7 different emotions (joy, fear, anger, sadness, disgust, shame, and guilt) expressed in short texts. The dataset is preprocessed and split into training and test sets.

## Methodology
The project uses machine learning classification algorithms (Naive Bayes, SVM, Random Forest) for comparison with the neural network. The neural network architecture consists of an embedding layer, a bidirectional LSTM layer, and a fully connected output layer with softmax activation. The model is trained on the training dataset and evaluated on the test dataset.
## Requirements
- Python 3.x
- Keras
- NumPy
- Pandas
- Scikit-learn
- NLTK
## How to run
1. Clone the repository:
```bash
git clone https://github.com/your-username/emotion-detection.git
```
2. Install the required packages:
```bash
pip install -r requirements.txt
```
## Results
The performance of the machine learning classification algorithms and neural network is evaluated using accuracy, precision, recall, and F1-score metrics. The results show that the neural network outperforms the machine learning classification algorithms in terms of accuracy and F1-score.

## Conclusion
The project demonstrates the use of machine learning classification algorithms and neural networks for emotion detection in textual data. The results show that the neural network outperforms the machine learning classification algorithms in terms of accuracy and F1-score. The project can be further extended to other datasets and domains.
