# Stepwise-Logistic-Regression-using-R-
Add files via upload
This R Markdown project focuses on analyzing and predicting customer responses (accept or reject) based on various features in the Gourmet Data. The dataset is preprocessed, cleaned, and analyzed using multiple techniques, including statistical summaries and machine learning algorithms.

Key Steps:
Data Cleaning: The dataset is loaded and cleaned by removing unnecessary columns and handling any inconsistencies or missing data.

Exploratory Data Analysis (EDA): The data is summarized using descriptive statistics and visualizations to uncover patterns in the data.

Preprocessing: Categorical variables like Response and Education are converted into factors. The Response variable is recoded into two levels: "accept" and "notaccept".

Modeling: The dataset is ready for predictive modeling using techniques such as logistic regression or decision trees (as seen from the libraries used).

Libraries Used:
caret: Machine learning package for model training

tidyverse: Data manipulation and visualization

skimr: Summarizing data

e1071: SVM and other classifiers

glmnet: Elastic net regularization for regression

ROCR: Performance evaluation for models

How to Run:
Clone the repository:
git clone https://github.com/gudythecoder/Stepwise-Logistic-Regression-using-R-.git

Install necessary packages:
install.packages(c("caret", "tidyverse", "skimr", "e1071", "glmnet", "Matrix", "ROCR"))

Run the R Markdown file:
rmarkdown::render("CustomerA.Rmd")
