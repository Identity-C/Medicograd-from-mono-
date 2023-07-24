# Medical Chatbot for Disease Prediction

This repository contains code for a medical chatbot that uses machine learning techniques to predict diseases based on patient transcripts. The chatbot is implemented using Python and utilizes the Scikit-learn library for Support Vector Machine (SVM) classification and TF-IDF vectorization.

## Contents

1. **`dataset.csv`:** The dataset file containing patient transcripts and corresponding disease labels.

2. **`chatbot.py`:** The main Python script that implements the medical chatbot.

3. **`README.md`:** The documentation file explaining the usage and details of the chatbot.

## Requirements

- Python 3.x
- Pandas
- Scikit-learn

## Usage

1. Ensure you have the required libraries installed by running `pip install pandas scikit-learn` in your Python environment.

2. Place the dataset file, `dataset.csv`, in the same directory as `chatbot.py`.

3. Run the `chatbot.py` script using the following command: `python chatbot.py`

4. The chatbot will start running, and you can interact with it by providing patient transcripts. Type "exit", "quit", or "bye" to terminate the chatbot.

## About the Model

The medical chatbot uses a Support Vector Machine (SVM) model with a linear kernel for disease classification. The patient transcripts are transformed into numerical features using TF-IDF vectorization. The model is trained on 50% of the provided dataset and tested on the remaining 50%.

## How the Chatbot Works

1. The chatbot greets the user and instructs them to enter a patient's transcript.

2. The user inputs the transcript.

3. The chatbot predicts the disease based on the provided transcript using the trained SVM model.

4. The predicted disease is displayed as the chatbot's response.

5. The chatbot continues to prompt for new transcripts until the user types "exit," "quit," or "bye."

## Note

- This chatbot is a basic example and may not be suitable for actual medical diagnosis purposes. It serves as a demonstration of how machine learning can be used for disease prediction based on textual data.

- The dataset used for training and testing the model must be appropriately labeled with patient transcripts and corresponding disease labels.

- Ensure that the dataset file is correctly formatted and contains the required columns ("transcript" and "topic").

- The accuracy and performance of the model depend on the quality and size of the dataset used for training.

- Feel free to experiment with different machine learning algorithms and feature extraction techniques to improve the chatbot's performance.

## Disclaimer

This chatbot is intended for educational and demonstration purposes only. It is not a substitute for professional medical advice or diagnosis. Always consult qualified healthcare professionals for medical concerns or conditions. The authors are not responsible for any decisions made based on the chatbot's predictions.

Please use this chatbot responsibly and ethically.
