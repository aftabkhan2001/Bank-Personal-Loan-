# BANK PERSONAL LOAN PREDICTION 
Harnessing the capabilities of machine learning, our project is dedicated to enhancing prediction algorithms tailored for personal loans. This initiative seeks to play a pivotal role in advancing customer retention strategies within the dynamic landscape of the banking sector.
![PL_blog_banner](https://github.com/aftabkhan2001/Bank-Personal-Loan-/assets/156090794/0de1aa9d-e23c-4686-9499-53c90d67f259)
# IMPORTANCE
Unleash the Power of Personal Bank Loans!

### Debt Simplified:
Why? Combine debts into one for manageable payments and potential interest savings.

### Emergency Rescue:
Why? Quick funds for unexpected bills, repairs, or unforeseen costs.

### Home Upgrade Shortcut:
Why? Finance renovations, repairs, or appliance upgrades effortlessly.

### Study Stress-Free:
Why? Cover tuition and educational expenses without worries.

### Life's Big Moments, Financed:
Why? Fund weddings, vacations, or special life events conveniently.

### Credit Boost:
Why? Timely repayments build a positive credit history effortlessly.

In a nutshell, personal bank loans simplify life's financial challenges, providing a shortcut to your goals. Easy, quick, and tailored for you!
![1_1BWK7tvR6_UZwcmaCQWvBQ](https://github.com/aftabkhan2001/Bank-Personal-Loan-/assets/156090794/0ed00b45-102a-4ff7-ab6f-730a3b3054ea)
# AIMS AND OBJECTIVES 
Empower Your Finances with Personal Loans!

### Instant Financial Aid:
Why? Immediate access to funds for your financial needs.
### Debt Harmony:
Why? Merge and handle high-interest debts with ease.
### Rapid Resources:
Why? Swift access to funds for urgent needs or unexpected expenses.
### Budget-Friendly Repayment:
Why? Enjoy structured plans for easy and affordable repayment.
### Your Way, Any Way:
Why? Utilize funds for a variety of personal needs—your choices, your rules.
### Credit Boosting Opportunity:+
Why? Build or enhance your credit scores while meeting your financial goals.
### Easy Street Borrowing:
Why? Simplify the borrowing process for short-term financial assistance.
Seize control of your financial journey—personal loans, your pathway to freedom!

![58809Screenshot from 2022-05-11 21-29-31](https://github.com/aftabkhan2001/Bank-Personal-Loan-/assets/156090794/573e2473-1c46-4717-b8ec-fa5ad770760a)
# ABOUT THE DATASETS 
Unveiling Banking Insights: A Quick Overview

This dataset dives deep into customer demographics and financial factors in the banking realm. With a keen eye on economic development, our focus is sharp—applying machine learning to predict loan acceptance and spot potential defaulters.

## Key Details in a Snap:

### Features Galore: Age, income, education, and more—essential elements explored.
### Target Variable: 'Personal Loan'—a sign of customer loan acceptance, albeit a bit lopsided.
Mission at Hand: Empowering Smart Banking

## Predictive Wizardry:
What? Crafting a machine learning model.
Why? Foreseeing loan acceptance, empowering informed decisions.
### Risk Radar:
What? Identifying potential defaulters.
Why? Curbing loan risks and optimizing financial resource distribution.
### End Game: Smarter Banking, Reduced Risks

In a nutshell, we're on a mission—to boost the bank's decision-making prowess, slash loan risks, and refine how financial resources flow. Join us in transforming data into banking wisdom.

![1_cnAWs_-xAWo_UXM2WWesyQ](https://github.com/aftabkhan2001/Bank-Personal-Loan-/assets/156090794/4ba1b7df-9610-4147-bf0b-e68b4924ec7f)
# OVERVIEW
Key Details About The Datasets:

### Number of records: Our data have a robust collection of data. Consisting of 5000 rows. Each record is very important
### Features/Columns : The dataset is characterized by a various set of features, each providing valuable insights into customer behavior. There are total 14 Columns
### Source Of Data: The dataset is sourced from Kaggle, ensuring reliability and relevance.
![Personal loan](https://github.com/aftabkhan2001/Bank-Personal-Loan-/assets/156090794/a75f9232-19d0-4cdf-a8ec-b485c740f292)

# MODEL USED 
![WhatsApp Image 2024-02-27 at 16 53 54_b35a6f84](https://github.com/aftabkhan2001/Bank-Personal-Loan-/assets/156090794/c67b41e6-8d6f-4f3e-b21b-af78581a004a)

# EVALUATION METRICS 
## ROC AUC CURVES WITH HYPERPARAMETER TUNING 

## Hyperparameter Tuning Boosts Model Performance
Post-tuning, ROC scores shine brighter:
### Logistic Regression: +0.95%
### Naive Bayes: +0.93%
### Support Vector Machine: +0.97%
Top Performer: Support Vector Machine
With the highest post-tuning ROC score, the Support Vector Machine steals the spotlight. Optimal choice for superior model performance compared to Logistic Regression and Naive Bayes. Decision made—Support Vector Machine leads the pack! 🚀

# CONCLUSION
In conclusion, the analysis reveals that the dataset contains a highly imbalanced target variable, with a majority of customers (4520) not taking personal loans (0) and a smaller number (480) taking loans (1).
Further exploration indicates that customers with educational backgrounds in Graduation and Professional categories are more likely to take personal loans compared to those with an Undergraduate education.
Family size also plays a role, with customers from families with 3 or 4 members showing a higher tendency to take personal loans.
The absence of a securities account seems to be associated with a higher likelihood of taking a personal loan, while having a Certificate of Deposit (CDAccount) is positively correlated with personal loan uptake.
Additionally, customers using online banking services are more inclined to have personal loans.
There is a negative trend where individuals with credit cards are less likely to take out personal loans.
Addressing the imbalanced target variable, the SMOTE (Synthetic Minority Over-sampling Technique) method has been employed along with standard scaling for numeric features (age, CCavg, mortgage, income).
Outliers are present but are not considered as error points.
Among the tested algorithms after the Hyperparammeter Tuning (Logistic Regression, Naive Bayes, and Support Vector Machine), SVM outperforms others across multiple metrics, including accuracy (0.95%), precision (0.74%), recall (0.84%), F1 score (0.79%) & Roc Auc Score (0.97%).
This suggests that SVM is the most suitable model for predicting personal loan uptake in this dataset

PRESENTED BY:AFTAB KHAN

![conclusion-mens-t-shirt](https://github.com/aftabkhan2001/Bank-Personal-Loan-/assets/156090794/30d6df5f-c9cd-4820-a852-3ccebe1c08be)

# DASHBOARD 

![Screenshot 2023-12-13 213722](https://github.com/aftabkhan2001/Bank-Personal-Loan-/assets/156090794/dc49849e-9422-4323-829b-60c3627f3ef9)

                                                                                           E







