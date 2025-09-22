# 🚜 Predicting the Sale Price of Bulldozers using Machine Learning

## 1. Problem Definition  
How well can we predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for?

---

## 2. Data  
The data is downloaded from the **Kaggle Bluebook for Bulldozers competition**:  
👉 [Dataset Link](https://www.kaggle.com/c/bluebook-for-bulldozers/data)

There are 3 main datasets:

- **Train.csv** → Training set, which contains data through the end of 2011.  
- **Valid.csv** → Validation set, which contains data from *January 1, 2012 - April 30, 2012*.  
  - Predictions are made on this set throughout the majority of the competition.  
  - Your score on this set is used to create the **public leaderboard**.  
- **Test.csv** → Test set (not released until the last week of the competition).  
  - Contains data from *May 1, 2012 - November 2012*.  
  - Your score on this set determines your **final rank** for the competition.  

### Key fields in `train.csv`:
- **SalesID** → Unique identifier of the sale  
- **MachineID** → Unique identifier of a machine (a machine can be sold multiple times)  
- **saleprice** → Price the machine sold for at auction (*only in train.csv*)  
- **saledate** → The date of the sale  

---

## 3. Evaluation  
The evaluation metric for this competition is **RMSLE (Root Mean Squared Log Error)** between the actual and predicted auction prices.  

📖 More details: [Kaggle Evaluation Page](https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation)

👉 Goal: **Minimize RMSLE**  

---

## 4. Features  
Kaggle provides a **data dictionary** detailing all of the features of the dataset.  

📑 View it here: [Data Dictionary (Google Sheets)](https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?usp=sharing)
