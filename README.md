# BERT-Driven QnA System
## Overview:
This project is a Question-Answering (QnA) system built using BERT, designed to handle complex and multi-turn conversations with context awareness. The model is trained on the CoQA dataset, which has been cleaned and formatted to enhance its effectiveness in extracting accurate answer spans from a given context.

## Features:
  * Data Preprocessing: Cleaned and formatted the CoQA dataset for effective model training.
  * Data Transformation: Converted raw data into a structured dataframe for better data handling.
  * BERT-based Model: Implemented a BERT Question-Answering model for precise answer extraction.
  * Context Awareness: Effectively maintains context across multiple questions in a conversation.
  * Multi-turn Conversations: Handles follow-up queries by preserving context from previous exchanges.

## Dataset:
The model is trained on the Conversational Question Answering (CoQA) dataset, which consists of multi-turn dialogues where each conversation is based on a given passage.

## Dependencies:
  * Python 3.x
  * Transformers (Hugging Face)
  * TensorFlow / PyTorch
  * Pandas
  * NumPy
  * Scikit-learn

## Results:
The model effectively extracts precise answer spans and maintains context continuity across multi-turn conversations, making it ideal for conversational AI applications.

## Future Improvements:
 * Fine-tuning with larger datasets for improved generalization.
 * Enhancing multi-turn response accuracy.
 * Integrating with a chatbot interface for real-time QnA interactions.
