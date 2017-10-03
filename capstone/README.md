# Machine Learning Nanodegree Capstone Project

## Kaggle Competition: 

For my MLND capstone project I chose to do the [Kaggle competition](https://www.kaggle.com/c/msk-redefining-cancer-treatment)
titled "Personalized Medicine: Redefining Cancer Treatment." The competition is about using natural language processing to determine
which class a piece of text (in this case medical liturature) belongs to. The class represents genetic mutations.

**Training/Testing Data:** Because this is a Kaggle competition I cannot post the training/testing data provided by them to Github. From Kaggle website: "Participants agree to use suitable measures to prevent persons who have not formally agreed to these Competition Rules from gaining access to the Data and agree not to transmit, duplicate, publish, redistribute or otherwise provide or make available the Data to any party not participating in the Competition"

The data can be downloaded from the competition website here:

https://www.kaggle.com/c/msk-redefining-cancer-treatment/data

## Software Requirements

Using Jupyter Notebook version 5.0

Python 3.5.3

iPython 6.1.0

keras 2.0.6

matplotlib 2.0.2

numpy 1.13.3

pandas 0.20.3

scikit-learn 0.19.0

seaborn 0.8

spacy 1.8.2

imbalanced-learn 0.3.0

tensorflow 1.0.0

**To download conda environment:** In a terminal or command window navigate to this directory and execute the following code:
```Bash
conda env create -f environment.yml
```
To activate environment:
+ Windows: `activate capstone`
+ Mac/Linux: `source activate capstone`

The glove text file (glove.6B.100d.txt) that should be in the "glove" folder is too big to post to github. It can be downloaded at this website:

https://nlp.stanford.edu/projects/glove/
