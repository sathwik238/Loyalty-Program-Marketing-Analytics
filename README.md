# Loyalty Program Marketing Analytics

This project focuses on leveraging a supermarket's loyalty program to analyze customer behavior and design targeted marketing campaigns for a new line of organic products. By utilizing analytics, we identify the most probable buyers from the loyalty program to ensure effective product penetration and marketing strategy.

---

## **Project Objective**

- To identify the most probable buyers of a newly launched organic product line.
- To leverage data from the supermarket's loyalty program (~250,000 participants) for targeted marketing.
- To optimize the distribution of sample kits to increase product penetration.

---

## **Business Case**

- **Client**: ABC Supermarket, a major player in the UK with multiple stores.
- **Marketing Strategy**:
  - 10% of loyalty program participants have already received sample kits.
  - The remaining sample kits (~90%) will be distributed to the most probable buyers, identified using analytics.
- **Goal**: Accelerate adoption of the organic product line.

---

## **Dataset**

The dataset contains anonymized loyalty program data, including:
- **Customer ID**: Unique identifier for loyalty program participants.
- **Demographics**: Age, gender, income group, etc.
- **Purchase History**: Categories of products purchased, frequency, and amounts.
- **Engagement**: Loyalty program engagement metrics (e.g., visits, points earned, redemptions).
- **Organic Product Interest**: Flags indicating prior interest in organic products.

---

## **Technologies Used**

- **Python**:
  - pandas, numpy: Data cleaning and manipulation
  - matplotlib, seaborn: Data visualization
  - scikit-learn: Machine learning models
  - imbalanced-learn: Handle class imbalance
- **GitHub**: Version control and collaboration

---

## **Model Workflow**

1. **Data Preprocessing**:
   - Load and clean loyalty program data.
   - Handle missing values and encode categorical variables.
2. **Exploratory Data Analysis (EDA)**:
   - Analyze purchase patterns and demographic trends.
   - Visualize feature distributions and correlations.
3. **Model Training**:
   - Train classification models to predict the likelihood of purchase.
   - Evaluate models using metrics such as precision, recall, and F1-score.
4. **Targeted Recommendations**:
   - Identify the top 90% of probable buyers for marketing campaigns.

---

## **How to Run the Project**

1. **Clone Repository**:
   ```bash
   git clone https://github.com/yourusername/Loyalty-Program-Marketing-Analytics.git
   cd Loyalty-Program-Marketing-Analytics
