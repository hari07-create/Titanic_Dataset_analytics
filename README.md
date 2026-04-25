Titanic_Dataset_analytics

📌 Project Overview
This project performs an end-to-end data analysis and predictive modeling on the classic **Titanic: Machine Learning from Disaster** dataset. The goal is to analyze the factors that influenced passenger survival and build a classification model to predict outcomes based on features like age, gender, and socio-economic status.

🛠️ Tech Stack
* Environment: Google Colab
* Language: Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

📊 Exploratory Data Analysis (EDA)
I conducted a deep dive into the dataset to identify patterns and correlations. Key visualizations included:
* Bar Graphs: To compare survival rates across different passenger classes and genders.
* Boxplots: Used to detect outliers in the 'Age' and 'Fare' distributions.
* Pie Charts: To visualize the overall proportion of survivors vs. non-survivors.
* Scatter Plots: To explore the relationship between age, fare, and survival.

⚙️ Data Preprocessing
To ensure model quality, I handled the following:
* Missing Values: Addressed null values in 'Age', 'Embarked', and 'Cabin' columns.
* Feature Encoding: Converted categorical variables (like Gender and Embarked) into numerical format for the model.
* Feature Scaling: Normalized data where necessary to improve model performance.

🤖 Modeling & Evaluation
I implemented a classification model to predict survival. The performance was evaluated using:
1.  Accuracy Rate: Providing a clear percentage of correct predictions.
2.  Confusion Matrix: To visualize the True Positives, True Negatives, False Positives, and False Negatives, ensuring a balanced understanding of model errors.

🚀 How to Run
1.  Open the `Titanic_Analysis.ipynb` file.
2.  Click the **"Open in Colab"** badge (if available) or upload the file to [Google Colab](https://colab.research.google.com/).
3.  Run the cells sequentially to see the analysis and model results.

## 📈 Key Insights
* Socio-economic status (Pclass) played a significant role in survival probability.
* Gender was a primary predictor, reflecting the "women and children first" protocol.
