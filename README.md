# Abbreviation-Disambiguation

## Abstract

What is the possibility for a Data Scientist to create a model that can read Medical Text and correctly classify the Medical Abbreviations to enable readers to make sense of the Medical Text in correct context?

Acronyms and abbreviations within clinical text are widespread, and their use continues to increase. Several reasons for this ongoing growth include adoption of electronic health record (EHR) systems with increased volume of electronic clinical notes accompanied by the wide usage of acronyms and abbreviations, the time-constrained nature of clinical medicine encouraging the use of shortened word forms, and a longstanding tradition of commonly using acronyms and abbreviations in clinical documentation.
 The process of understanding the precise meaning of a given acronym or abbreviation in texts is one of several key functions of automated medical natural language processing (NLP) systems and is a special case of word sense disambiguation (WSD).
 
This project uses the freely available Medical Dataset for Abbreviation Disambiguation (MeDAL) downloaded directly from Kaggle. This project employs the implementation of some of the well-known NLP libraries like spacy and gensim to understand the context of a medical text and based on that context predict what the expanded form of an Abbreviation (if any) is in that medical text.


## Data Source

The Data used in this project has been collected from Kaggle. 

## Repository Flow

Please open the files in the Given order to clearly understand the Project/Data Flow.

### Order of Files:


Step 1- Data Wrangling and EDA.ipynb

Step 2- Data Preprocessing.ipynb

Step 3- Data Modeling.ipynb

### Documentation

1. Project Proposal.pdf
2. Project Report.pdf
3. Presentation.pptx


### The Folder Structure Definition:

Data: Contains the Orginal unaltered Dataset.

Train: Contains the dataset which will be used for training the model.

Validation: Contains the dataset which will be used for Validating the model.

Test: Contains the dataset which will be used for Testing the model.
