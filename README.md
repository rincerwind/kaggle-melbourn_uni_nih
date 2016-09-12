# kaggle-melbourn_uni_nih
==============================
Kaggle Melbourne University AES/MathWorks/NIH Seizure Prediction

Predict seizures in long-term human intracranial EEG recordings

# Getting Started
!!! Note, the script still doesn't work because I don't know how to pass through the authentication phase in Kaggle !!!

Run src/data/download_dataset1.py to download and extract the first training and test sets.

# Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── downloads      <- The downloaded data
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    |
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    |   ├── data           <- Scripts to acquire and manipulate the data
    │   │   └── download_dataset1.py
    │   │
    │   ├── preprocess     <- Scripts to turn raw data into suitable features that will be used in modelling
    │   │   └── preprocess.py
