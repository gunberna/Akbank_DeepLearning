# Akbank_DeepLearning
The initialization processes and aftermath of the bootcamp program. The dataset wheats were used and a CNN model was trained in order to predict ilnesses of wheats via image data.

## Importance 
The early diagnosis of plant diseases is quite significant for the economy and health of the general nation. With the help of convolutional neural networks, such diseases can be detected through data as little as a single picture. Later the training set could be improved with house plants and an app could be made via the trained model.

## Information concerning the Dataset
The dataset consists of labeled images of wheat leaves affected by various diseases, including healthy samples. These images were preprocessed and resized to 128×128 pixels for efficient model training.

## Methods & Methodology
A Convolutional Neural Network (CNN) was developed and trained to classify wheat diseases based on image data. Hyperparameter tuning was conducted using different learning rates and batch sizes, and Grad-CAM was used for visual model interpretation.

## Bottleneck
The model took a while to run and the hyperparameter tunning code was not completely executed, a kaggle notebook was used for the GPU, but as I monitored the CPU and GPU usage I noticed that GPU was seldom used hence there was a huge time constraint. The LLM models I've consulted has suggested the dataset was  not large enough to trigger the GPU yet I did see it transitioning sometimes.

## Outcomes and Aftermath
The accuracy level is not much promising but has improved after parameter tunning, more development in this area was needed.

https://www.kaggle.com/code/bernaozbasaran/akbank-deeplearning
