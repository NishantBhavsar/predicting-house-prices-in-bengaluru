# Predicting house prices in Bengaluru

### competition & Data source:
[https://www.machinehack.com/course/predicting-house-prices-in-bengaluru/](https://www.machinehack.com/course/predicting-house-prices-in-bengaluru/)

### Data:
- The train and test data will consist of various features that describe that property in Bengaluru.
- Each row contains fixed size object of features. There are 9 features and each feature can be accessed by its name.

##### Features:
1. Area_type – describes the area
2. Availability – when it can be possessed or when it is ready(categorical and time-series)
3. Location – where it is located in Bengaluru (Area name)
4. Size – in BHK or Bedroom (1-10 or more)
5. Society – to which society it belongs
6. Total_sqft – size of the property in sq.ft
7. Bath – No. of bathrooms
8. Balcony – No. of the balcony

##### Target variable:
- Price – Value of the property in lakhs(INR)

#### Train dataset:
- Contains all the features and target variable.
- Contains 13,321 records.  

#### Test dataset:
- Contains all the features.
- Contains 1,481 records.

### Problem statement:
With the given 9 features(categorical and continuous) build a model to predict the price of houses in Bengaluru.

### Evaluation Metric:
- Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted price value and the logarithm of the observed sales price.
- Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.

### Project Directory layout:

```bash
.
├── code
│   └── Data_preparation_and_Analysis.ipynb
├── input
│   ├── sample_submission.xlsx
│   ├── test.csv
│   └── train.csv
├── README.md
└── submissions
```