# ExtraaLearn Lead Conversion Prediction

## Project Overview

ExtraaLearn is an EdTech startup that offers upskilling and reskilling programs in cutting-edge technologies. The company generates a large number of leads through its website, mobile app, marketing campaigns, referrals, and other channels.

The goal of this project is to build a machine learning classification model that predicts whether a lead is likely to convert into a paid customer. The model can help ExtraaLearn prioritize high-potential leads and improve sales and marketing efficiency.

## Business Objective

The objectives of this project are to:

- Analyze lead behavior and identify factors associated with conversion.
- Build machine learning models to predict lead conversion.
- Compare model performance using classification metrics.
- Identify the profile of leads most likely to convert.
- Provide actionable business recommendations.

## Dataset

The dataset contains lead-level information and interaction details with ExtraaLearn.

Key variables include:

- `age`: Age of the lead
- `current_occupation`: Professional, Unemployed, or Student
- `first_interaction`: Website or Mobile App
- `profile_completed`: Low, Medium, or High
- `website_visits`: Number of website visits
- `time_spent_on_website`: Total time spent on the website
- `page_views_per_visit`: Average pages viewed per visit
- `last_activity`: Most recent interaction type
- `print_media_type1`: Newspaper ad exposure
- `print_media_type2`: Magazine ad exposure
- `digital_media`: Digital ad exposure
- `educational_channels`: Education channel exposure
- `referral`: Referral source
- `status`: Target variable, where 1 means converted and 0 means not converted

## Project Structure

```text
extraalearn-lead-conversion-prediction/
├── data/
│   └── Potential_Customers_Prediction.csv
├── models/
│   ├── final_model.joblib
│   ├── feature_columns.joblib
│   └── preprocessing_info.joblib
├── notebooks/
│   └── extraalearn-lead-conversion-prediction.ipynb
├── reports/
│   ├── figures/
│   └── model_comparison.csv
├── .gitignore
├── README.md
└── requirements.txt