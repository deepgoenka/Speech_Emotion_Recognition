# Speech Emotion Recognition

This repository contains a Speech Emotion Recognition (SER) model that can recognize various emotions in speech, including Angry, Stressful, Painful, Prank, Neutral, Sad, and Abusive voices. The model achieves an impressive accuracy of 95.5% on the evaluation dataset.

# Table of Contents
* Overview
* Dataset
* Model Architecture
* Usage
* Results
* Contributing
* License

# Overview
Speech Emotion Recognition is a challenging task in the field of Natural Language Processing and Audio Signal Processing. This project aims to develop a model that can accurately classify emotions in speech. The model uses deep learning techniques to extract relevant features from the audio data and predict the corresponding emotion category.

# Dataset
The SER model is trained on a diverse dataset of speech recordings, carefully labeled with seven emotion categories: Angry, Stressful, Painful, Prank, Neutral, Sad, and Abusive voices. The dataset contains audio samples from various sources and contexts to ensure a robust and representative training.

# Model Architecture
The Speech Emotion Recognition (SER) model in this repository is composed of four Conv1D layers and two Dense layers. This architecture has been specifically designed for speech emotion recognition tasks and has proven to be effective in achieving a high accuracy of 95.5% on the evaluation dataset.

# Usage
To use the speech emotion recognition model, follow these steps:
1. Clone this repository to your local machine.
2. Install the required dependencies specified in the requirements.txt file.
3. Prepare your audio data or use the provided sample dataset.
4. Run the recognize_emotion.py script, providing the path to the audio file as input.
5. The model will process the audio and output the predicted emotion category.
Feel free to customize the script or integrate the model into your own applications for real-time emotion recognition.

# Results
The speech emotion recognition model achieves an accuracy of 95.5% on the evaluation dataset. This high accuracy demonstrates the effectiveness of the model in accurately predicting emotions in speech. However, please note that the model's performance may vary depending on the input data and the specific context.

<p align="center">
    <img width="500" src="![image](https://github.com/deepgoenka/Speech_Emotion_Recognition/assets/71036685/61a180e1-62ea-4591-9251-e035c6f12b2f)" alt="Minimax Algorithm">
</p>

<p align="center">
    <img width="500" src="![image](https://github.com/deepgoenka/Speech_Emotion_Recognition/assets/71036685/d7f6899e-754e-418e-86de-eb0f5f7e53ab)" alt="Minimax Algorithm">
</p>

# Contributing
Contributions to this project are welcome! If you find any issues or have ideas for improvements, please submit a pull request or open an issue. Let's work together to make this speech emotion recognition model even better!

# License
Feel free to use, modify, and distribute the code for both commercial and non-commercial purposes. However, kindly attribute the original authors by linking back to this repository.
