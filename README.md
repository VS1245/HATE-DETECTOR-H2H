# HATE-DETECTOR-H2H
## Description
H2H (Hate 2 Health) is a hate detection system that takes tweets as inputs and predicts whether the tweet contains toxic, severe toxic, obscene, threat, insult, or identity hate content. It aims to identify and flag harmful content on social media platforms to promote healthier online interactions.

## Installation
To use H2H, follow these steps:

* Install Python and Jupyter Notebook on your machine.
* Download the dataset used for training the model from Kaggle.
* Clone or download this repository to your local machine.
* Open the code.ipynb notebook in Jupyter Notebook.
* Follow the steps provided in the notebook to train the model and make predictions.

## Usage
Once you have set up the project, you can use H2H to analyze tweets for hate content. Simply input the text of the tweet into the model, and it will output whether the tweet contains toxic, severe toxic, obscene, threat, insult, or identity hate content.

## Dataset
The project uses the Jigsaw Toxic Comment Classification Challenge dataset from Kaggle. The dataset contains comments from Wikipedia discussions, along with labels for various types of toxicity.

## Model Performance
The model achieved an accuracy of 93.75% and a precision of 50% on the test dataset. The accuracy and precision can be further improved by adjusting the layers in the model architecture.

## Contents
The repo contains 2 files 'code.ipynb' which conatins the code and 'output.txt' contains the some outputs.
Example -
WELCOME TO HATE DETECTOR: H2H_
1/1 ━━━━━━━━━━━━━━━━━━━━ 0s 106ms/step_
tweet: "I'll kill you"_
toxic: True_
severe_toxic: False_
obscene: False_
threat: False_
insult: False_
identity_hate: False_

## Contributing
Contributions to H2H are welcome! If you would like to contribute to the project, feel free to fork the repository, make your changes, and submit a pull request.
