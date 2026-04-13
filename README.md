# Movie-Revenue-Correlation-Analysis

​**Project Overview**
​In this project, I conducted an Exploratory Data Analysis (EDA) on a dataset of over 7,000 movies to identify the key factors that drive financial success in the film industry. The goal was to move beyond industry assumptions and use statistical methods to quantify which features (e.g., Budget, Company, User Rating) actually move the needle for Gross Revenue.

​**Key Insights**
​#Budget is King: A high Pearson Correlation (0.75) confirms that production budget remains the strongest predictor of a film's gross earnings.
​#Public Voice Matters: User Votes (0.63) showed a significantly higher correlation with revenue than the actual Critic Score (0.19).
​#Brand vs. Capital: Statistical testing revealed that the production company (e.g., Disney, Warner Bros) has a much lower impact on revenue than the actual capital invested in the project.
​
**Technical Stack**
​#Language: Python
​#Libraries: * Pandas: Data cleaning, handling null values, and date formatting.
​#Seaborn & Matplotlib: Heatmaps, scatter plots, and regression analysis.
​#NumPy: Mathematical operations.
​#Scikit-learn: Label Encoding for categorical variables.
​
**Project Workflow**
​#Data Cleaning: Audited a 7,000-row dataset to remove duplicates, fill missing values, and standardize date formats.
​#Feature Engineering: Applied Label Encoding to convert categorical strings (Genre, Company, Director) into numerical data to enable correlation mapping.
​#Correlation Mapping: Utilized the Pearson method to generate a correlation matrix across all numeric and encoded features.
​#Visualization: Developed regression plots to visualize the "fan-out" effect of high-budget investments and heatmaps to identify "hot zones" of influence.
<img width="1274" height="879" alt="Movie Revenue slide 1" src="https://github.com/user-attachments/assets/95245a2e-ae55-4173-b1ad-102ec38d0d7b" />
<img width="1303" height="868" alt="Movie Revenue slide 2" src="https://github.com/user-attachments/assets/49b88994-d9b0-4ecf-a23b-6137b205c8ad" />
<img width="1145" height="868" alt="Movie Revenue slide 3" src="https://github.com/user-attachments/assets/5b0f1dc3-c64b-4ed6-9322-3b01289e9d4a" />
<img width="1231" height="885" alt="Movie Revenue slide 4" src="https://github.com/user-attachments/assets/a9b5b83e-b493-4d6d-83d7-441a9f38912d" />
