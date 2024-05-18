<center><h1 style="background-color:none; color:tomato; font-size:36px; font-weight:bold; font-family:Adobe Hebrew;" >✨Explanotry Data Analysis and Comparison  of Machine learning Algorithms for BigMart Sales Prediction✨</h1></center>

**`Project Description`**

Big Mart is a retail chain that operates both online and across multiple physical locations. The company's data scientist has collected 2013 sales data for 1559 products across 10 stores in various cities. This data includes sales amounts, along with specific attributes of each product and store. Using this data, the company aims to forecast future sales for each product at a particular store. This will help adjust their business strategy for future operations. Therefore, the goal of this project is to act as a data scientist, explore the collected data through Exploratory Data Analysis, and build a predictive model to forecast product sales at individual outlets.

**`Main project Tasks`**

**`I. Data Loading, Cleaning and Preprocessing`**

- The dataset is available on Kaggle. Hence, import/load the dataset from kaggle using kaggle api to working directory of the code, be it local machine or cloud storage.
- First `Develop an overview` that includes key details about the datasets, such as data types, structure, and summary statistics. This comprehensive view will help identify errors, inconsistencies, or patterns, aiding in further data cleaning and preprocessing.'
- Identify and handle dataset and corrosponding columns with `missing values and duplicates`.
- Identify and handle `Irregularities in Data Entries` - data schema consistence
- Inspecting data for any outliers and treatment of those `outliers`

**`II. Explanotary Data Analysis`**

During Exploratory Data Analysis (EDA), we use plots like histograms, box plots, scatterplots, and density plots to visualize the features and target data. This helps us understand their distribution and central tendency, extracting insights crucial for effective feature engineering. Our analysis covers Univariate, Bivariate, Multivariate, and time series analyses for a thorough understanding of the dataset's characteristics and patterns.

**`II. Feature Engineering`**
Feature engineering is the process of transforming raw data into more effective inputs for supervised machine learning and statistical modeling. Here's how we do it:

- We identify the most `relevant features` based on our EDA, using domain knowledge or feature ranking algorithms.
- If necessary, we `create new features` from existing ones, such as lag features or date and time features from timestamp data.
- We `encode and scale features`. This involves transforming categorical features into numerical representations through techniques like label encoding or one-hot encoding. We also scale features to ensure they're on a similar scale, improving the performance of certain algorithms.

**`IV. Model Selection, Evaluation, and Hyperparameter Tuning`**

After preparing the feature and target data and dividing them into training and validation sets, we perform the following steps:

- Model Selection: We choose a set of candidate models or model architectures. The goal is to find a model that balances predictive performance with computational efficiency and interpretability.
- Model Evaluation: We assess the performance of the chosen models on unseen data. This helps determine how well the model generalizes to new observations (test data) using appropriate evaluation metrics. For regression, these metrics involve squared error. We also use cross-validation to obtain more reliable estimates of model performance by assessing its performance on multiple subsets of the data.
- Hyperparameter Tuning: Once the best models has been selected, we fine-tune  models hyperparameters to further improve  its performance. 

Finally, we validate the selected model on test data, indentify important features for the model and save model for future use.
