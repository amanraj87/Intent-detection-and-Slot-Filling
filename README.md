## Hindi NLP Project: Intent Detection and Slot Filling with Genetic Algorithm Optimization
#### Project Overview
This project implements an advanced Natural Language Processing (NLP) system for intent detection and slot filling in Hindi. It leverages deep learning techniques and evolutionary algorithms to create a robust model capable of understanding and extracting information from Hindi text inputs.
Key Components

#### Data Preparation

Translation of an English dataset to Hindi using Google Translate API
Data cleaning and preprocessing
Dataset splitting into training, validation, and testing sets


#### Intent Detection

Utilization of BERT (bert-base-multilingual-cased) for feature extraction
Fine-tuning of the BERT model for intent classification
Implementation of a custom dataset class for efficient data handling


#### Slot Filling

Development of a BiLSTM-based model on top of BERT embeddings
Custom dataset and model classes for slot filling task


#### Model Training

Separate training loops for intent detection and slot filling models
Use of CrossEntropyLoss and AdamW optimizer
Validation process to monitor model performance


#### Hyperparameter Optimization

Implementation of a Genetic Algorithm (GA) using the DEAP library
Optimization of key hyperparameters such as learning rate and hidden layer size
Fitness evaluation based on validation loss


#### Performance Visualization

Plotting of training and validation losses over epochs
Visualization of GA optimization progress



#### Technical Highlights

Multi-task learning approach combining intent detection and slot filling
Use of transfer learning with pre-trained multilingual BERT
Implementation of evolutionary computation for hyperparameter tuning
Handling of Hindi text processing and model adaptation for non-English language

This project demonstrates a comprehensive approach to building an NLP system for a non-English language, incorporating advanced machine learning techniques and optimization strategies.
