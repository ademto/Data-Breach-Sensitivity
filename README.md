# Data-Breach-Sensitivity


### <a name="_axa630mjc0c1"></a>**Project Title: Data Analysis and Machine Learning for Data Breach Sensitivity**
#### <a name="_7ppl82ahuzla"></a>**Objective**
#### Analyze data breaches and predict the sensitivity of breached data using machine learning techniques to provide actionable insights into data security.
#### <a name="_b48zetlqmk15"></a>**Data Description**
- #### **Dataset**: Contains information about data breaches with the following fields:
  - #### Name: Name of the breached entity.
  - #### Title: Title or description of the breach.
  - #### Domain: Domain associated with the breach.
  - #### BreachDate: Date when the breach occurred.
  - #### AddedDate: Date when the breach was added to the database.
  - #### ModifiedDate: Date when the breach details were last modified.
  - #### PwnCount: Number of records breached.
  - #### Description: Description of the breach.
  - #### LogoPath: URL to the logo of the breached entity.
  - #### DataClasses: Types of data exposed (e.g., Email addresses, Names).
  - #### IsVerified: Whether the breach is verified.
  - #### IsFabricated: Whether the breach is fabricated.
  - #### IsSensitive: Indicates if the breached data is sensitive.
  - #### IsRetired: Whether the breach record is retired.
  - #### IsSpamList: Indicates if the breach is on a spam list.
  - #### IsMalware: Indicates if malware is involved.
  - #### IsSubscriptionFree: Indicates if the breach involves free subscription data.
- #### **Data Cleaning:**
  - #### Addressed missing values by imputing or filling them.
  - #### Standardized date formats for consistency.
  - #### Removed irrelevant columns to streamline analysis.
#### <a name="_l9litcde2kgu"></a>**Methodology**
- #### **Data Preprocessing:**
  - #### Handled null values by imputation or removal.
  - #### Standardized and formatted date fields for consistency.
  - #### Encoded categorical variables (e.g., IsVerified, IsSensitive) using one-hot encoding for machine learning compatibility.
- #### **Exploratory Data Analysis (EDA):**
  - #### Visualized distributions of key variables such as IsSensitive and IsVerified.
  - #### Identified trends and patterns in breach occurrences and data sensitivity.
  - #### Utilized plots to show class distributions and feature importance.
- #### **Machine Learning:**
  - #### **Algorithm Used:** Random Forest Classifier.
  - #### **Feature Selection:** Identified important features contributing to data sensitivity using feature importance scores from the Random Forest model.
  - #### **Model Training and Evaluation:**
    - #### Evaluated model performance using metrics such as accuracy, precision, recall, and F1-score.
    - #### Conducted cross-validation to ensure model robustness.
#### <a name="_984mwn34ufrq"></a>**Results**
####
- #### **Visualizations:**
  - #### Feature Importance Plot: Shows the relative importance of features in predicting data sensitivity.
  - #### Class Distribution Plot: Displays the distribution of sensitive vs. non-sensitive breaches.
  - #### Breaches Over Time: Line plot showing breach frequency over time.
  - #### Bar Charts: Distribution of attributes such as IsVerified, IsSensitive, IsMalware, and IsSpamList.
  - #### Word Cloud: Visualization of common terms in breach descriptions.
  - #### Box Plots: Relationship between PwnCount and breach attributes (IsVerified, IsSensitive).
  - #### Stacked Bar Chart: Distribution of categories (Verified, Sensitive, Malware, Spam List).
#### <a name="_6ri3xtn2sfj9"></a>**Code Repository**
- #### **GitHub Repository:[ ](https://github.com/ademto/Data-Breach-Sensitivity)<https://github.com/ademto/Data-Breach-Sensitivity>**
  - #### <a name="_y6bmvjriqcct"></a>Contains all code, data files, and documentation.
  - #### <a name="_pkj89x8qzi3i"></a>Includes a detailed README file with instructions for running the analysis and model.


