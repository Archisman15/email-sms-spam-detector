# Email/SMS Spam Detector App

This project is a simple Email/SMS Spam Detector built using Machine Learning techniques. It helps classify whether a given message is spam or not spam.

## Overview

The project uses a Machine Learning model trained on a dataset containing examples of spam and non-spam messages. The model is deployed using a Streamlit web application, allowing users to input a message and get a prediction of whether it's spam or not.

## Technologies Used

- Python
- Streamlit
- NLTK (Natural Language Toolkit)
- Scikit-learn


## Model Training

The model used in this project is trained using a combination of text preprocessing techniques and a machine learning algorithm. The `model.pkl` file contains the trained model, while the `vectorizer.pkl` file contains the TF-IDF vectorizer used to transform input messages.

## Usage

Once the application is running, users can input a message into the provided text area and click the "Predict" button. The application will then classify the message as either spam or not spam.

## Deployment Link

https://email-sms-spam-detector-archisman15.streamlit.app/


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
