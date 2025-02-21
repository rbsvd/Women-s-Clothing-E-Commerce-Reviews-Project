# Women-s-Clothing-E-Commerce-Reviews-Project

### Objective and Scope
**Objective**: The goal of this project is to analyze e-commerce reviews data to predict whether a product will be recommended and provide actionable insights for e-commerce strategies. The specific objectives are:
1. Understand the relationship between different numeric features and the target variable (recommendation status).
2. Develop and evaluate machine learning models to accurately predict product recommendations.
3. Provide actionable insights and recommendations based on the analysis.

**Scope**:
1. Exploratory Data Analysis (EDA) to understand the data distribution, detect any anomalies, and explore relationships between features.
2. Preprocessing steps such as handling missing values, encoding categorical variables, and feature scaling.
3. Development of machine learning models, including Logistic Regression and Decision Tree Classifier.
4. Evaluation of model performance using appropriate metrics.
5. Generation of insights and recommendations based on the analysis results.

### Methodology
**Data Preprocessing**:
- **Data Cleaning**: Handled missing values and ensured clean column names.
- **Encoding Categorical Variables**: Applied one-hot encoding to categorical features and label encoding to the target variable.
- **Feature Scaling**: Standardized numeric features to ensure consistent data distribution and model performance.

**Model Development**:
- **Logistic Regression**: Used logistic regression to predict product recommendations. The model was trained and evaluated using accuracy and classification metrics.
- **Decision Tree Classifier**: Used decision tree classifier to predict product recommendations. The model was evaluated similarly to the logistic regression model.

### Results and Insights
**Logistic Regression**:
- Accuracy: 82.50%
- Provided balanced predictions across different review sentiments.

**Decision Tree Classifier**:
- Accuracy: 73.03%
- Helped identify distinct customer groups based on their purchasing behavior and review sentiments.

### Recommendations
1. **Personalization**: Use customer data to personalize recommendations and offers. For example, if a customer frequently reviews products positively, offer them discounts on similar items. Utilize the logistic regression model to predict customer preferences.
2. **Customer Segmentation**: Segment customers based on their purchasing behavior, review sentiments, and engagement. Tailor marketing campaigns to target specific segments effectively. The decision tree model can help identify distinct customer groups.
3. **Enhanced User Experience**: Analyze review word count and sentiment to identify areas of improvement in product descriptions and customer service. Ensure that detailed, positive reviews are highlighted to build trust and credibility.
4. **Loyalty Programs**: Implement loyalty programs that reward customers for consistent positive feedback and high engagement. Use predictions from both models to identify potential loyal customers and encourage repeat purchases.
5. **Content Strategy**: Focus on creating engaging content that resonates with customers. Analyze the title and review word count to determine what type of content is most effective in driving customer interest and satisfaction.
6. **Product Recommendations**: Leverage your models to create a dynamic product recommendation system that adapts to customer preferences and browsing behavior, increasing the likelihood of conversions.

### Final Report
**Key Findings**:
- Logistic Regression and Decision Tree models were effective in predicting the target variable.
- Logistic Regression achieved an accuracy of 0.8250, while Decision Tree achieved an accuracy of 0.7303.
- The EDA highlighted significant correlations between numeric features and the target variable, providing insights into the data patterns.

**Visuals**:
- Included visualizations such as tables and summary statistics to support the findings.
- Visual tools were used to present data intuitively and identify patterns and trends.

**Limitations**:
- The analysis assumed that the data was accurately recorded and cleaned. Any errors or anomalies in the data could affect the model's accuracy.
- The dataset's diversity in terms of the distribution of classes was not considered, which might limit the model's generalizability.

**Potential for Further Exploration**:
- Further exploration could involve incorporating more features or different data sources to enhance prediction accuracy.
- Investigating the impact of different machine learning algorithms and hyperparameter tuning to improve model performance.
- Exploring advanced techniques such as ensemble methods or deep learning to achieve better results.

### Environment Setup
To ensure the project runs smoothly, please follow the steps below to set up the environment:

**Prerequisites**:
- Operating System: Windows 11
- Programming Language: Python 3.12.6
- Dependencies: Pandas, Numpy, Matplotlib, Scikit-learn, NLP, TextBlob, Pandas etc.
- Environment: Jupyter Notebook

### HTML Report
The detailed analysis can be viewed by downloading or viewing the raw HTML report:

- [View Raw HTML Report](Women's Clothing E-Commerce Reviews Project.html)
- [View the code in Python file format](https://drive.google.com/file/d/1h83wJBLUbjYbjGQLqKuljRf4Zrvk9wSa/view?usp=drive_link)

*Note: The file is too large to be rendered directly on GitHub, but you can download and open it in your browser.*

Feel free to customize this outline to fit your project's specific needs!
