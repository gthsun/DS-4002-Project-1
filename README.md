# DS 4002 Project 1 - Skytrax Airline Review Sentiment Analysis

## Software Used
For data preprocessing, sentiment analysis, and evaluation, we used Jupyter Notebook with Python.
Alongside Python, the packages "pandas" and "re" need to be installed for data preprocessing. The packages "pandas", "torch", "transformers", and "pathlib" are needed for sentiment analysis. We utilized (and recommend) "Anaconda" to handle Python dependencies.

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
│
└── data_dictionary.md
```


## Instructions for Reproduction of Results
To reproduce our results, first download the data...

Next, complete sentiment analysis by firstly installing the packages required for sentiment analysis as mentioned above in this README before running the code. An alternative recommendation is to install Anaconda and enter a conda virtual environment (which is what we did). Ensure that your directory's structure for your existing files so far matches the structure of our directory (which should mainly be data right now). Afterwards, download the 'sentiment_analysis.ipynb' notebook from the SCRIPTS folder and run the entire file, once again ensuring the structure is the same. It may take >40 min to finish running. The conclusion of the notebook running should result in a 'with_sentiments' folder in the DATA directory with a new .csv file with sentiment analysis scores attached to each review, and a 'with_mismatch' folder in the DATA directory with a new .csv file with the mismatch indicators attached to each review.

Finally, get results for hypothesis testing by making sure to install and load in the two R packages as mentioned above in this README. Download the 'hypothesis_testing.Rmd' script from the SCRIPTS folder and run the entire file (after making sure to set the working directory to the same one as where the cleaned data files are located). Output produced in R by using the hypothesis testing script should mimic the output as presented in the OUTPUT folder exactly.
