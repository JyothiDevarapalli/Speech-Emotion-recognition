# Speech-Emotion-recognition
This recognizes human emotions and affective states from speech signals. Imagine a computer recognizing if someone is happy, sad, or excited just by analyzing their voice. It's like adding emotional intelligence to technology!

# Input 
The input to our project is audio data containing spoken words. We use datasets that include people speaking with different emotions – happy, sad, angry, surprised, and more.

**DATA SETS:**

**Crowd-sourced Emotional Mutimodal Actors Dataset (Crema-D)** - This is a dataset created by collecting videos from actors who emote various emotions. It includes both posed and naturally occurring emotions.

**Ryerson Audio-Visual Database of Emotional Speech and Song (Ravdess)** - This database contains speech and song recordings, encompassing various emotions. It includes both acted and improvised expressions.

**Surrey Audio-Visual Expressed Emotion (Savee)** - A dataset with audio recordings from male actors expressing different emotions. The dataset is particularly suitable for speech emotion analysis.

**Toronto emotional speech set (Tess)** -  TESS comprises naturalistic emotional expressions in speech. It covers a range of emotions, and the speakers include both native and non-native English speakers beneficial for developing models that need diverse emotional speech data.

The link of the datasets is given in seperate file. 

# Implementation 

1. Data Preparation: Audio datasets with labeled emotions are collected from Kaggle.  The Popular ones include Crema-D, RAVDESS, TESS, and SAVEE. Each dataset offers a variety of emotions and situations.

2. Feature Extraction: Convert raw audio data into features that our computer can understand. These features include zero-crossing rate, chroma_stft, MFCCs, RMS value, and MelSpectrogram.

3. Data Augmentation: To improve learning, create more synthetic data by adding variations like noise, stretching, and pitching to our original audio samples.

4. Model Training: Convolutional Neural Network (CNN) is used to train the computer. It learns patterns from the extracted features to associate them with different emotions.

5. Evaluation: After training, test the model on a separate set of audio data to see how well it predicts emotions. We check metrics like accuracy, precision, recall, and the confusion matrix.

# Result
The output is the computer's prediction of the emotion expressed in the audio. For example, it might say, "I think the speaker is happy" or "This sounds like an angry tone."

This model achieved an accuracy of 61% on the test data. It excelled in recognizing surprise and anger due to distinct audio patterns.


