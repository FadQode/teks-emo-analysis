# Introduction
The goal of this system is to provide users with a platform that can understand and classify their emotional state from diary entries. The system processes the text input, predicts the user's emotional state, and then generates constructive feedback tailored to their emotional needs.

access this through github: https://github.com/FadQode/teks-emo-analysis

The primary components of this system are:
RoBERTa: A pre-trained transformer model that trained on emotion dataset for emotion classification.
Gamma: A Generative ai that is fine tuned on counseling dataset to give proper ouput to user

## Open With Colab
Kindly open the ipynb file in this repository and click open in colab on the top cell

## Some Note
- emotion analysis used to asses and slit dataset while roberta_can_read_emotion used for training the model 
- To run all cell in these jupyter file you will need Hugging face account and wanb account then generate your own token for training
- not all cell will need both but mostly espically the one to take dataset, train, and save model will definetly need it

## Dataset used for this is from:
1. https://huggingface.co/datasets/OpenAssistant/oasst1/blob/main/data/train-00000-of-00001-b42a775f407cee45.parquet
2. https://huggingface.co/datasets/elvanromp/emosi_tweet

## Trained model in this project available in hugging face:
1. https://huggingface.co/FadQ/gemma-2b-diary-consultaton-chatbot
2. https://huggingface.co/FadQ/roberta-can-read-emotion
