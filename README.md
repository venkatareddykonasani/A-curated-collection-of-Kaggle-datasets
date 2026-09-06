# 📊 46 Real-World Kaggle Datasets for Data Science & Machine Learning Projects

A curated collection of **46 Kaggle datasets** across Banking, Finance, Insurance, Retail, E-commerce, Marketing, Telecom, Healthcare, HR, Transportation, Real Estate, and Supply Chain.

These datasets are suitable for:

* Exploratory Data Analysis
* Data Cleaning & Preprocessing
* Feature Engineering
* Machine Learning
* Classification & Regression
* Customer Analytics
* Time-Series Forecasting
* Recommendation Systems
* Clustering & Segmentation
* Fraud & Risk Analytics
* Business Analytics Projects
* Portfolio & Capstone Projects

---

## 🏦 Banking, Credit Risk & Financial Services

| # | Dataset Name                              | Kaggle Link                                                                                                            | Domain / Industry      | Business Problem                       | Approx. Dataset Size                   | Key Techniques Possible                                              | Sample Columns                                                       | Dataset Short Description                                                                                     |
| - | ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ---------------------- | -------------------------------------- | -------------------------------------- | -------------------------------------------------------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| 1 | Give Me Some Credit                       | <a href="https://www.kaggle.com/c/GiveMeSomeCredit" target="_blank">Open Kaggle</a>                                    | Banking / Credit Risk  | Predict financial distress/default     | ~250K borrowers                        | EDA, Logistic Regression, XGBoost, Imbalance Handling, Scorecards    | age, MonthlyIncome, DebtRatio, NumberOfDependents, SeriousDlqin2yrs  | Consumer credit-scoring dataset for predicting serious delinquency within two years.                          |
| 2 | Home Credit Default Risk                  | <a href="https://www.kaggle.com/competitions/home-credit-default-risk" target="_blank">Open Kaggle</a>                 | Banking / Lending      | Predict loan repayment capability      | 300K+ applications, multiple tables    | Joins, Aggregation, Feature Engineering, LightGBM, XGBoost           | TARGET, AMT_INCOME_TOTAL, AMT_CREDIT, DAYS_BIRTH, NAME_CONTRACT_TYPE | Rich multi-table lending dataset containing applications, bureau records, previous loans and payment history. |
| 3 | Lending Club Loan Data                    | <a href="https://www.kaggle.com/datasets/wordsforthewise/lending-club" target="_blank">Open Kaggle</a>                 | FinTech / P2P Lending  | Predict loan default and borrower risk | 2M+ loan records                       | EDA, Credit Scoring, Classification, Survival Analysis               | loan_amnt, int_rate, grade, annual_inc, loan_status                  | Large lending dataset containing borrower, loan and credit characteristics.                                   |
| 4 | Default of Credit Card Clients            | <a href="https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset" target="_blank">Open Kaggle</a> | Banking / Credit Cards | Predict credit-card default            | ~30K customers                         | Classification, Feature Selection, SHAP, EDA                         | LIMIT_BAL, SEX, EDUCATION, AGE, PAY_0, BILL_AMT1                     | Credit-card customer demographics, repayment history and billing information.                                 |
| 5 | American Express Default Prediction       | <a href="https://www.kaggle.com/competitions/amex-default-prediction" target="_blank">Open Kaggle</a>                  | Credit Cards           | Predict future customer default        | Millions of observations               | Temporal Aggregation, LightGBM, CatBoost, Ensembles                  | customer_ID, S_2, D_*, S_*, P_*, B_*                                 | Advanced longitudinal credit-risk dataset with multiple monthly observations per customer.                    |
| 6 | Credit Card Fraud Detection               | <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud" target="_blank">Open Kaggle</a>                      | Banking / Payments     | Detect fraudulent transactions         | ~285K transactions                     | Anomaly Detection, SMOTE, Classification, PR-AUC                     | Time, V1-V28, Amount, Class                                          | Highly imbalanced transaction dataset designed for fraud-detection modelling.                                 |
| 7 | IEEE-CIS Fraud Detection                  | <a href="https://www.kaggle.com/c/ieee-fraud-detection" target="_blank">Open Kaggle</a>                                | Payments / E-commerce  | Detect online transaction fraud        | ~1M transactions, hundreds of features | Feature Engineering, Joins, CatBoost, XGBoost                        | TransactionAmt, ProductCD, card1, addr1, DeviceType, isFraud         | Complex fraud dataset combining transaction, identity and device information.                                 |
| 8 | Santander Customer Transaction Prediction | <a href="https://www.kaggle.com/c/santander-customer-transaction-prediction" target="_blank">Open Kaggle</a>           | Banking                | Predict customer transaction behaviour | ~200K rows, 200 features               | Classification, Feature Selection, Boosting, Ensembling              | target, var_0, var_1, var_2, var_3                                   | High-dimensional anonymized banking classification dataset.                                                   |
| 9 | Santander Product Recommendation          | <a href="https://www.kaggle.com/c/santander-product-recommendation" target="_blank">Open Kaggle</a>                    | Banking / CRM          | Recommend financial products           | Millions of customer-month records     | Recommendation Systems, Multilabel Classification, Temporal Features | fecha_dato, ncodpers, renta, age, ind_*_ult1                         | Predict additional financial products customers are likely to purchase.                                       |

---

## 🛡️ Insurance Analytics

| #  | Dataset Name                           | Kaggle Link                                                                                                                  | Domain / Industry     | Business Problem                    | Approx. Dataset Size       | Key Techniques Possible                                           | Sample Columns                                                      | Dataset Short Description                                                               |
| -- | -------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | --------------------- | ----------------------------------- | -------------------------- | ----------------------------------------------------------------- | ------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| 10 | Porto Seguro Safe Driver Prediction    | <a href="https://www.kaggle.com/competitions/porto-seguro-safe-driver-prediction" target="_blank">Open Kaggle</a>            | Motor Insurance       | Predict insurance claim probability | ~595K records              | Classification, Feature Engineering, Boosting, Imbalance Handling | target, ps_ind_*, ps_reg_*, ps_car_*                                | Anonymized policyholder dataset for predicting future motor insurance claims.           |
| 11 | Allstate Claims Severity               | <a href="https://www.kaggle.com/c/allstate-claims-severity" target="_blank">Open Kaggle</a>                                  | Insurance             | Predict monetary severity of claims | ~189K rows, 130+ variables | Regression, Categorical Encoding, XGBoost, Feature Engineering    | cat1-cat116, cont1-cont14, loss                                     | Insurance claims regression dataset containing categorical and continuous risk factors. |
| 12 | Prudential Life Insurance Assessment   | <a href="https://www.kaggle.com/competitions/prudential-life-insurance-assessment" target="_blank">Open Kaggle</a>           | Life Insurance        | Automate insurance risk assessment  | ~59K applications          | Ordinal Classification, Feature Engineering, Boosting             | Product_Info_*, Ins_Age, BMI, Employment_Info_*, Response           | Predict underwriting risk categories from applicant information.                        |
| 13 | Health Insurance Cross Sell Prediction | <a href="https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction" target="_blank">Open Kaggle</a>  | Insurance / Marketing | Predict vehicle-insurance purchase  | ~381K customers            | Classification, Segmentation, Imbalance Handling                  | Gender, Age, Driving_License, Vehicle_Age, Annual_Premium, Response | Identify existing insurance customers likely to purchase vehicle insurance.             |
| 14 | Travel Insurance Prediction            | <a href="https://www.kaggle.com/datasets/tejashvi14/travel-insurance-prediction-data" target="_blank">Open Kaggle</a>        | Travel Insurance      | Predict insurance purchase          | ~2K customers              | Classification, EDA, Segmentation                                 | Age, Employment Type, AnnualIncome, FrequentFlyer, TravelInsurance  | Customer-level dataset for predicting travel-insurance purchases.                       |
| 15 | Insurance Claim Prediction             | <a href="https://www.kaggle.com/datasets/easonlai/sample-insurance-claim-prediction-dataset" target="_blank">Open Kaggle</a> | Insurance             | Predict claim likelihood            | Medium                     | Classification, EDA, Risk Segmentation                            | age, gender, vehicle_age, premium, claim                            | Policyholder and risk characteristics for insurance claim modelling.                    |

---

## 📡 Telecom & Customer Churn

| #  | Dataset Name                  | Kaggle Link                                                                                               | Domain / Industry | Business Problem                   | Approx. Dataset Size | Key Techniques Possible                                 | Sample Columns                                                                       | Dataset Short Description                                                     |
| -- | ----------------------------- | --------------------------------------------------------------------------------------------------------- | ----------------- | ---------------------------------- | -------------------- | ------------------------------------------------------- | ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- |
| 16 | Telco Customer Churn          | <a href="https://www.kaggle.com/datasets/blastchar/telco-customer-churn" target="_blank">Open Kaggle</a>  | Telecom           | Predict customer churn             | 7,043 customers      | Classification, Segmentation, SHAP, Retention Modelling | tenure, Contract, MonthlyCharges, TotalCharges, InternetService, Churn               | Customer subscriptions, account and service information for churn prediction. |
| 17 | Orange Telecom Churn          | <a href="https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets" target="_blank">Open Kaggle</a> | Telecom           | Identify customers likely to leave | ~5K records          | Classification, Feature Importance, Retention Analytics | account_length, international_plan, total_day_minutes, customer_service_calls, churn | Telecom usage and customer-service data for churn modelling.                  |
| 18 | Bank Customer Churn Modelling | <a href="https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling" target="_blank">Open Kaggle</a> | Banking / CRM     | Predict bank customer exit         | ~10K customers       | Classification, Segmentation, Explainability            | CreditScore, Geography, Gender, Age, Balance, IsActiveMember, Exited                 | Banking customer demographic and account information for churn prediction.    |

---

## 📣 Marketing & Advertising

| #  | Dataset Name                         | Kaggle Link                                                                                                         | Domain / Industry   | Business Problem                  | Approx. Dataset Size | Key Techniques Possible                                       | Sample Columns                                                | Dataset Short Description                                                 |
| -- | ------------------------------------ | ------------------------------------------------------------------------------------------------------------------- | ------------------- | --------------------------------- | -------------------- | ------------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------------------- |
| 19 | Bank Marketing Dataset               | <a href="https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset" target="_blank">Open Kaggle</a>      | Banking / Marketing | Predict term-deposit subscription | ~45K contacts        | Classification, Campaign Analytics, Segmentation              | age, job, marital, balance, duration, campaign, deposit       | Telemarketing campaign data for improving customer targeting.             |
| 20 | Customer Personality Analysis        | <a href="https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis" target="_blank">Open Kaggle</a> | Retail / Marketing  | Segment and understand customers  | ~2.2K customers      | Clustering, RFM, PCA, Campaign Analysis                       | Income, Kidhome, Recency, MntWines, NumWebPurchases, Response | Household, purchasing and campaign data for customer segmentation.        |
| 21 | Avazu CTR Prediction                 | <a href="https://www.kaggle.com/c/avazu-ctr-prediction" target="_blank">Open Kaggle</a>                             | Digital Advertising | Predict advertisement clicks      | ~40M rows            | CTR Modelling, Feature Hashing, Logistic Regression, Boosting | hour, C1, banner_pos, site_id, app_id, device_id, click       | Large-scale mobile advertising dataset for click-through-rate prediction. |
| 22 | Criteo Display Advertising Challenge | <a href="https://www.kaggle.com/c/criteo-display-ad-challenge" target="_blank">Open Kaggle</a>                      | AdTech              | Predict display-ad clicks         | ~45M rows            | Sparse Modelling, Feature Hashing, Embeddings, Deep Learning  | Label, I1-I13, C1-C26                                         | Massive anonymized advertising dataset for CTR prediction.                |

---

## 🛒 Retail & E-commerce

| #  | Dataset Name                     | Kaggle Link                                                                                                                     | Domain / Industry     | Business Problem                               | Approx. Dataset Size           | Key Techniques Possible                                       | Sample Columns                                                             | Dataset Short Description                                                                    |
| -- | -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | --------------------- | ---------------------------------------------- | ------------------------------ | ------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| 23 | Black Friday Sales               | <a href="https://www.kaggle.com/datasets/sdolezel/black-friday" target="_blank">Open Kaggle</a>                                 | Retail                | Understand and predict customer spending       | ~550K transactions             | Regression, Segmentation, EDA                                 | User_ID, Product_ID, Gender, Age, Occupation, Purchase                     | Retail purchase records useful for customer spending and product analysis.                   |
| 24 | Olist Brazilian E-Commerce       | <a href="https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce" target="_blank">Open Kaggle</a>                           | E-commerce            | Analyze marketplace performance                | ~100K orders, 9 tables         | SQL Joins, RFM, CLV, Delivery Analytics, NLP                  | order_id, customer_id, product_id, price, freight_value, review_score      | Multi-table marketplace dataset covering customers, sellers, payments, products and reviews. |
| 25 | Instacart Market Basket Analysis | <a href="https://www.kaggle.com/c/instacart-market-basket-analysis" target="_blank">Open Kaggle</a>                             | Grocery / E-commerce  | Predict products customers reorder             | 3M+ orders                     | Association Rules, Recommendation Systems, Sequence Modelling | order_id, user_id, product_id, aisle_id, reordered                         | Grocery transaction history for basket analysis and personalized recommendations.            |
| 26 | Online Retail II                 | <a href="https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci" target="_blank">Open Kaggle</a>                          | Retail                | Customer segmentation and purchasing analytics | ~1M transactions               | RFM, CLV, Clustering, Cohort Analysis                         | Invoice, StockCode, Description, Quantity, InvoiceDate, Price, Customer ID | Online retail transaction dataset for customer-value and purchasing-pattern analysis.        |
| 27 | Retailrocket Recommender Dataset | <a href="https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset" target="_blank">Open Kaggle</a>                        | E-commerce            | Recommend products from browsing behaviour     | ~2.7M events                   | Collaborative Filtering, Implicit Feedback, Sequence Models   | timestamp, visitorid, event, itemid, transactionid                         | User events containing product views, cart additions and purchases.                          |
| 28 | Rossmann Store Sales             | <a href="https://www.kaggle.com/c/rossmann-store-sales" target="_blank">Open Kaggle</a>                                         | Retail                | Forecast store sales                           | ~1M observations, 1,115 stores | Time Series, Regression, Feature Engineering, Boosting        | Store, Date, Sales, Customers, Promo, StateHoliday                         | Historical store sales combined with promotions and competitor information.                  |
| 29 | Walmart Store Sales Forecasting  | <a href="https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting" target="_blank">Open Kaggle</a>                   | Retail                | Forecast department-level sales                | 400K+ weekly records           | Time Series, Regression, Holiday Effects                      | Store, Dept, Date, Weekly_Sales, IsHoliday                                 | Weekly retail sales forecasting dataset with store, department and holiday information.      |
| 30 | M5 Forecasting Accuracy          | <a href="https://www.kaggle.com/c/m5-forecasting-accuracy" target="_blank">Open Kaggle</a>                                      | Retail / Supply Chain | Forecast item-level unit sales                 | 30K+ series, ~1,900 days       | Hierarchical Forecasting, Lag Features, LightGBM              | item_id, dept_id, cat_id, store_id, state_id, d_1...d_1941                 | Large hierarchical Walmart sales forecasting dataset.                                        |
| 31 | Store Item Demand Forecasting    | <a href="https://www.kaggle.com/c/demand-forecasting-kernels-only" target="_blank">Open Kaggle</a>                              | Retail / Supply Chain | Forecast product demand                        | ~913K observations             | Time Series, Lag Features, Seasonality, Boosting              | date, store, item, sales                                                   | Five years of daily store-item sales history for demand forecasting.                         |
| 32 | Mall Customer Segmentation       | <a href="https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python" target="_blank">Open Kaggle</a> | Retail / CRM          | Identify customer segments                     | ~200 customers                 | K-Means, Hierarchical Clustering, PCA                         | CustomerID, Gender, Age, Annual Income, Spending Score                     | Customer demographic and spending data for segmentation exercises.                           |

---

## 🏥 Healthcare

| #  | Dataset Name                 | Kaggle Link                                                                                                     | Domain / Industry | Business Problem             | Approx. Dataset Size | Key Techniques Possible                                   | Sample Columns                                                              | Dataset Short Description                                                  |
| -- | ---------------------------- | --------------------------------------------------------------------------------------------------------------- | ----------------- | ---------------------------- | -------------------- | --------------------------------------------------------- | --------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| 33 | Medical Appointment No Shows | <a href="https://www.kaggle.com/datasets/joniarroba/noshowappointments" target="_blank">Open Kaggle</a>         | Healthcare        | Predict missed appointments  | ~110K appointments   | Classification, Feature Engineering, Operations Analytics | PatientId, Gender, Age, ScheduledDay, AppointmentDay, SMS_received, No-show | Patient and scheduling data for understanding missed medical appointments. |
| 34 | Hospital Readmissions        | <a href="https://www.kaggle.com/datasets/dubradave/hospital-readmissions" target="_blank">Open Kaggle</a>       | Healthcare        | Predict hospital readmission | ~25K records         | Classification, Healthcare Analytics, Feature Importance  | age, time_in_hospital, medical_specialty, num_lab_procedures, readmitted    | Patient encounter information useful for identifying readmission risk.     |
| 35 | Diabetes Dataset             | <a href="https://www.kaggle.com/datasets/mathchi/diabetes-data-set" target="_blank">Open Kaggle</a>             | Healthcare        | Predict diabetes             | ~768 observations    | Classification, EDA, Feature Scaling                      | Pregnancies, Glucose, BloodPressure, BMI, Age, Outcome                      | Classic structured clinical dataset for binary disease prediction.         |
| 36 | Heart Failure Prediction     | <a href="https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction" target="_blank">Open Kaggle</a>  | Healthcare        | Predict heart disease        | ~918 patients        | Classification, Feature Importance, Explainability        | Age, Sex, ChestPainType, Cholesterol, MaxHR, HeartDisease                   | Cardiovascular indicators used to predict heart disease.                   |
| 37 | Stroke Prediction            | <a href="https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset" target="_blank">Open Kaggle</a> | Healthcare        | Predict stroke risk          | ~5K patients         | Classification, Imbalance Handling, SHAP                  | gender, age, hypertension, heart_disease, avg_glucose_level, bmi, stroke    | Patient demographic and clinical risk factors for stroke prediction.       |

---

## 👥 Human Resources

| #  | Dataset Name                     | Kaggle Link                                                                                                                   | Domain / Industry | Business Problem                           | Approx. Dataset Size | Key Techniques Possible                                   | Sample Columns                                                                  | Dataset Short Description                                                              |
| -- | -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ----------------- | ------------------------------------------ | -------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| 38 | IBM HR Employee Attrition        | <a href="https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset" target="_blank">Open Kaggle</a>    | Human Resources   | Predict employee attrition                 | 1,470 employees      | Classification, People Analytics, SHAP                    | Age, BusinessTravel, JobRole, MonthlyIncome, JobSatisfaction, Attrition         | Employee dataset for identifying factors associated with workforce attrition.          |
| 39 | HR Analytics Job Change          | <a href="https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists" target="_blank">Open Kaggle</a> | HR / Recruitment  | Predict whether candidate seeks job change | ~19K candidates      | Classification, Imbalance Handling, Recruitment Analytics | city, gender, education_level, experience, company_size, training_hours, target | Candidate profiles and employment characteristics for predicting job-change intention. |
| 40 | Salary Prediction Classification | <a href="https://www.kaggle.com/datasets/ayessa/salary-prediction-classification" target="_blank">Open Kaggle</a>             | HR / Compensation | Predict income category                    | Tens of thousands    | Classification, Encoding, Feature Selection               | age, workclass, education, occupation, hours-per-week, income                   | Demographic and employment characteristics for income-category prediction.             |

---

## 🚕 Transportation & Mobility

| #  | Dataset Name             | Kaggle Link                                                                                                             | Domain / Industry | Business Problem                 | Approx. Dataset Size | Key Techniques Possible                            | Sample Columns                                                                     | Dataset Short Description                                                                    |
| -- | ------------------------ | ----------------------------------------------------------------------------------------------------------------------- | ----------------- | -------------------------------- | -------------------- | -------------------------------------------------- | ---------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| 41 | NYC Taxi Trip Duration   | <a href="https://www.kaggle.com/c/nyc-taxi-trip-duration" target="_blank">Open Kaggle</a>                               | Transportation    | Predict taxi trip duration       | ~1.45M trips         | Regression, Geospatial Features, Temporal Features | pickup_datetime, pickup_longitude, pickup_latitude, passenger_count, trip_duration | Large trip-level dataset for predicting journey duration from location and time information. |
| 42 | NYC Taxi Fare Prediction | <a href="https://www.kaggle.com/c/new-york-city-taxi-fare-prediction" target="_blank">Open Kaggle</a>                   | Transportation    | Predict taxi fares               | Millions of trips    | Regression, Geospatial Engineering, Sampling       | fare_amount, pickup_datetime, pickup_longitude, pickup_latitude, passenger_count   | Large geospatial regression problem for estimating taxi fares.                               |
| 43 | Uber Pickups NYC         | <a href="https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city" target="_blank">Open Kaggle</a> | Mobility          | Analyze and forecast ride demand | Millions of pickups  | Geospatial Analysis, Clustering, Time Series       | Date/Time, Lat, Lon, Base                                                          | Uber pickup records for geographical and temporal demand analysis.                           |

---

## 🏠 Real Estate

| #  | Dataset Name                                 | Kaggle Link                                                                                                               | Domain / Industry      | Business Problem                     | Approx. Dataset Size                | Key Techniques Possible                                 | Sample Columns                                                                       | Dataset Short Description                                                                |
| -- | -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | ---------------------- | ------------------------------------ | ----------------------------------- | ------------------------------------------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| 44 | House Prices: Advanced Regression Techniques | <a href="https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques" target="_blank">Open Kaggle</a> | Real Estate            | Predict residential sale prices      | 1,460 training homes, 79 predictors | Feature Engineering, Regression, Random Forest, XGBoost | OverallQual, GrLivArea, YearBuilt, GarageCars, Neighborhood, SalePrice               | Detailed Ames housing dataset containing extensive residential property characteristics. |
| 45 | Zillow Home Value Prediction                 | <a href="https://www.kaggle.com/competitions/zillow-prize-1" target="_blank">Open Kaggle</a>                              | Real Estate / PropTech | Improve automated property valuation | Millions of property records        | Regression, Geospatial Features, Boosting, Missing Data | parcelid, bathroomcnt, bedroomcnt, calculatedfinishedsquarefeet, latitude, longitude | Large property-characteristics dataset for automated home-value modelling.               |

---

## 💼 Sales & CRM

| #  | Dataset Name      | Kaggle Link                                                                                          | Domain / Industry | Business Problem                 | Approx. Dataset Size | Key Techniques Possible               | Sample Columns                                                          | Dataset Short Description                                                                       |
| -- | ----------------- | ---------------------------------------------------------------------------------------------------- | ----------------- | -------------------------------- | -------------------- | ------------------------------------- | ----------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| 46 | Sample Sales Data | <a href="https://www.kaggle.com/datasets/kyanyoga/sample-sales-data" target="_blank">Open Kaggle</a> | Sales / CRM       | Analyze sales and customer value | ~2.8K order lines    | RFM, CLV, Clustering, Sales Analytics | ORDERNUMBER, QUANTITYORDERED, SALES, PRODUCTLINE, CUSTOMERNAME, COUNTRY | Transactional sales dataset useful for customer-value, product and geographical sales analysis. |

---

# 🎯 Recommended Datasets for Serious Portfolio Projects

| Dataset                          | Recommended Project                        |
| -------------------------------- | ------------------------------------------ |
| Home Credit Default Risk         | End-to-End Credit Risk Scoring System      |
| Lending Club                     | Loan Default & Risk-Based Pricing          |
| American Express Default         | Customer Default Early-Warning System      |
| IEEE-CIS Fraud Detection         | Real-Time Transaction Fraud Detection      |
| Porto Seguro                     | Insurance Claim Risk Prediction            |
| Allstate Claims Severity         | Insurance Loss Severity Modelling          |
| Santander Product Recommendation | Banking Next-Best-Product Engine           |
| Olist E-Commerce                 | Customer 360 & Marketplace Analytics       |
| Instacart                        | Personalized Grocery Recommendation Engine |
| Retailrocket                     | E-Commerce Recommendation System           |
| Rossmann                         | Store-Level Sales Forecasting              |
| M5 Forecasting                   | Hierarchical Retail Demand Forecasting     |
| Telco Customer Churn             | Customer Churn & Retention System          |
| Medical Appointment No Shows     | Appointment No-Show Risk Prediction        |
| NYC Taxi                         | Trip Duration & Demand Analytics           |
| Zillow                           | Automated Property Valuation Model         |

---

# 🧠 Machine Learning Problems Covered

## Classification

* Credit Default Prediction
* Fraud Detection
* Customer Churn
* Insurance Claims
* Employee Attrition
* Healthcare Risk Prediction
* Marketing Response

## Regression

* House Price Prediction
* Insurance Claim Severity
* Taxi Fare Prediction
* Trip Duration Prediction

## Time-Series Forecasting

* Retail Sales Forecasting
* Product Demand Forecasting
* Store-Level Forecasting
* Transportation Demand Forecasting

## Clustering

* Customer Segmentation
* RFM Segmentation
* Behavioural Segmentation

## Recommendation Systems

* Product Recommendation
* Market Basket Analysis
* Financial Product Recommendation
* E-commerce Personalization

## Anomaly Detection

* Credit Card Fraud
* Transaction Fraud
* Insurance Risk

---

# ⭐ Complexity Guide

## Beginner-Friendly

* Telco Customer Churn
* Bank Customer Churn
* IBM HR Attrition
* Medical Appointment No Shows
* Bank Marketing
* House Prices
* Stroke Prediction

## Intermediate

* Lending Club
* Porto Seguro
* Allstate Claims
* Customer Personality Analysis
* Online Retail II
* Retailrocket
* Rossmann Store Sales
* NYC Taxi Trip Duration

## Advanced

* Home Credit Default Risk
* American Express Default Prediction
* IEEE-CIS Fraud Detection
* Santander Product Recommendation
* Avazu CTR Prediction
* Criteo Display Advertising
* Olist E-Commerce
* Instacart Market Basket Analysis
* M5 Forecasting
* Zillow Home Value Prediction

---

# 📌 Suggested End-to-End Project Workflow

1. Business Problem Definition
2. Dataset Understanding
3. Exploratory Data Analysis
4. Data Quality Analysis
5. Missing Value Treatment
6. Outlier Analysis
7. Feature Engineering
8. Feature Selection
9. Model Development
10. Hyperparameter Tuning
11. Model Evaluation
12. Explainability / SHAP
13. Business Interpretation
14. Dashboard / Visualization
15. Model Deployment
16. Project Documentation

---

# 🔗 Source

Datasets and competitions listed in this repository are publicly available through:

<a href="https://www.kaggle.com/" target="_blank">Kaggle</a>

Please refer to each individual Kaggle dataset or competition page for licensing, competition rules, and usage restrictions.

---

# ⭐ About This Collection

The purpose of this collection is to identify datasets that can support **realistic, industry-oriented Data Science and Machine Learning projects**, rather than only small demonstration datasets.

Industries covered:

**Banking • Financial Services • Insurance • Telecom • Retail • E-commerce • Marketing • Healthcare • Human Resources • Transportation • Real Estate • Supply Chain**
