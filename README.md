# Plot First, Model Second: Exploring Transformers and the Power of Data Visualization

## Project Overview

In this notebook, we'll explore one of the most intuitive -- and universally applicable -- business use cases for machine learning: predicting customer churn. After all, who wants to lose a customer?

For this deep dive, we'll take a look at a popular data science/ML dataset -- the **"Telco-Customer-Churn.csv" dataset**, which was originally created by IBM. The tech giant designed this synthetic dataset to simulate customer behavior at a fictitious telecom company for use with Watson Analytics and other AI tools. You can read all about it right here on GitHub.

Along the way, we'll learn all about data preprocessing, and powerful and elegant transformers like `SimpleImputer`, `OneHotEncoder`, `make_pipeline`, and `make_column_transformer`.

At the close of the pipeline-building process, we end up at a final insight -- it's just not the one we were expecting.

Here's the path we'll be following:

## The Road Map:
- Import pandas and load the dataset for initial exploration
- Begin preprocessing, check the data types
- Visualize `Churn` -- the target variable
- Set X and y, and split the training and test sets
- Import the transformers and build the pipeline
- Evaluate model performance with 5-fold cross-validation
- Build a scaled pipeline
- Evaluate the performance of the scaled models
- Plot first, model second: The scaled takeaway

## Tools & Libraries Used

- **Jupyter Notebook** — the interactive environment used to explore, build, and document the entire modeling process  
- **Python 3.12.7** — base language powering all modeling, iteration, and data prep   
- **scikit-learn** - for preprocessing, building pipelines, modeling, and evaluation
- **matplotlib** - for data visualization
- **pandas and numpy** - for data manipulation and analysis

## Acknowkedgements
This notebook was inspired by an assignment designed by Tao Li, Associate Professor in the Department of Information & Analytics at Santa Clara University's Leavey School of Business. As always, thanks to the Professor for creating assignments that inspire further investigation.
