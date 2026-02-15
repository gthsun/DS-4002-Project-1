# DS 4002 Project 1 - Skytrax Airline Review Sentiment Analysis

## Software Used
For data preprocessing, sentiment analysis, and evaluation, we used Jupyter Notebook with Python.
Alongside Python, the packages "pandas" and "re" need to be installed for data preprocessing. The packages "pandas", "torch", "transformers", and "pathlib" are needed for sentiment analysis. 

For hypothesis testing, model development, and additional evaluation, we used RStudio with R. 
Alongside R, the packages "tidyverse" and "caret" need to be installed for hypothesis testing. 

We all worked with Mac OS.

## Map of Documentation
```
DS-4002-Project-1 Folder Outline
│
├── DATA
│   ├── cleaned
│   │   ├── bases
│   │   │   ├── Cabin
│   │   │   │   ├── .ipynb_checkpoints
│   │   │   │   │   └── cabin_base_cabin_Business Class-checkpoint.csv
│   │   │   │   ├── cabin_base_cabin_Business Class.csv
│   │   │   │   ├── cabin_base_cabin_Economy.csv
│   │   │   │   ├── cabin_base_cabin_First Class.csv
│   │   │   │   ├── cabin_base_cabin_Premium Economy.csv
│   │   │   │   └── cabin_base_cabin_Unknown.csv
│   │   │   ├── Traveler
│   │   │   │   ├── traveler_base_traveler_Business.csv
│   │   │   │   ├── traveler_base_traveler_Couple Lesisure.csv
│   │   │   │   ├── traveler_base_traveler_FamilyLeisure.csv
│   │   │   │   ├── traveler_base_traveler_Solo Leisure.csv
│   │   │   │   └── traveler_base_traveler_Unknown.csv
│   │   │   └── .DS_Store
│   │   ├── data/.ipynb_checkpoints
│   │   │   ├── airline-checkpoint.csv
│   │   │   └── airport-checkpoint.csv
│   │   ├── .DS_Store
│   │   ├── airline_all_cols.csv
│   │   ├── airline_cleaned.csv
│   │   └── airline_dummies_only.csv
│   │
│   ├── original
│   │   ├── airline.csv
│   │   ├── airport.csv
│   │   ├── lounge.csv
│   │   └── seat.csv
│   │
│   ├── with_mismatch
│   │   └── airline_with_mismatch.csv
│   │
│   └── with_sentiments
│       └── airline_cleaned_with_sentiment.csv
│
├── OUTPUT
│   ├── cfnmatrix_results.png
│   ├── logregmodel_results.png
│   ├── modelfit_results.png
│   └── oddsratio_results.png
│
├── SCRIPTS
│   ├── cleaning_data.ipynb
│   ├── hypothesis_testing.Rmd
│   └── sentiment_analysis.ipynb
│
├── LICENSE.md
│
└── README.md
```


## Instructions for Reproduction of Results
To reproduce our results, first download the data...

Next, complete sentiment analysis by...

Finally, get results for hypothesis testing by making sure to install and load in the two R packages as mentioned above in this README. Download the 'hypothesis_testing.Rmd' script from the SCRIPTS folder and run the entire file (after making sure to set the working directory to the same one as where the cleaned data files are located). Output produced in R by using the hypothesis testing script should mimic the output as presented in the OUTPUT folder exactly.