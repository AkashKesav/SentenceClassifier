# Sentence Classifier
This repository contains code for the "Contradictory, My Dear Watson" project, which leverages Hugging Face's transformers for natural language processing tasks. The primary objective is to classify statements into entailment, neutral, or contradictory
# Table Of Contents
* Dataset
* Models Used
* Model Architecture
* Training
* Evaluation
* Contributions and Acknowledgements
* Code Errors and Fix Plans
# Datasets
The dataset used for this project is available on Kaggle.
# Models Used
This project uses the BERT Base multilingual uncased model from Hugging Face's transformers library
# Model Architecture
The model architecture primarily revolves around the BERT (Bidirectional Encoder Representations from Transformers) model, fine-tuned for the task of classification
# Training
To train the model, execute the cells in the notebook step-by-step. The training process includes loading the dataset, preprocessing, setting up the model, and running the training loop.
# Evaluation
The evaluation metrics used in this project include accuracy and loss. After training, the model's performance is evaluated on a separate test set to ensure it generalizes well.
# Contributions and Acknowledgements
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes. Acknowledgements go to Hugging Face for their transformers library and the creators of the dataset
# Code Errors and Fix Plans
## Identified Issues
* The model begins to overfit after the 2nd or 3rd epoch
* The model's learning plateaus at an accuracy of approximately 63-64%
## Planned Solutions
* To address these issues, I plan to implement a different transformer architecture to improve generalization and performance

