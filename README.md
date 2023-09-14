# Reddit gender classification
---

## Purpose

  The purpose of this project is to correctly classify the gender of some Reddit users based 
  only on their comments ( so the data will contain the date of the comments, the
  subreddit which they belong and the comment itself)

---           

## Contents 

  - Main project ( Reddit gender classification.ipynb)
  - Data folder containing train (features and targets) and test( without targets) 

---

## Usage

  The main file contains a pre-processing pipeline using dummy encoding for categorical features (subreddits)
  and a simple TF-IDF encoding process, while the date features are not really relevant so they are not considered
  in the process. After downloading the files together, run the main also considering different parameters for the
  pipeline above described.
  The test targets are not included because this project is intented to be a Kaggle competion, in which those data
  are not visible, so the main script final output is only a file containing predictions.

---

Author : Andrea Caputo

Mail : andrea.caputo275@edu.unito.it
