# Introduction
The goal of this system is to provide users with a platform that can understand and classify their emotional state from diary entries. The system processes the text input, predicts the user's emotional state, and then generates constructive feedback tailored to their emotional needs.

The primary components of this system are:
RoBERTa: A pre-trained transformer model that trained on emotion dataset for emotion classification.
Gamma: A Generative ai that is fine tuned on counseling dataset to give proper ouput to user

## OPen With Colab
Kindly open the ipynb file in this repository and click open in colab on the top cell

## Dataset used for this is from:
https://huggingface.co/datasets/OpenAssistant/oasst1/blob/main/data/train-00000-of-00001-b42a775f407cee45.parquet
https://huggingface.co/datasets/elvanromp/emosi_tweet

## Trained model in this project available in hugging face:
https://huggingface.co/FadQ/gemma-2b-diary-consultaton-chatbot
https://huggingface.co/FadQ/Roberta_can_read_Emotion
