# 🏦 Bank Customer Analytics Project

A comprehensive data science project analyzing bank customer behavior through **Churn Prediction** and **Customer Segmentation** to derive actionable business insights.

##  Project Overview

This project analyzes bank customer data to understand customer behavior patterns, predict churn probability, and segment customers into meaningful groups for targeted marketing and retention strategies.

##  Key Objectives

- **Churn Prediction**: Identify customers at risk of leaving the bank
- **Customer Segmentation**: Group customers based on behavioral and demographic patterns
- **Business Intelligence**: Generate actionable insights for marketing and retention strategies


##  Analysis Summary

###  Churn Prediction Analysis (`BankChurners.ipynb`)

**Key Findings from Exploratory Data Analysis:**

- **Demographics Impact**: Educational background doesn't significantly influence card preference, suggesting demographic-based marketing may not yield better results
- **Statistical Analysis**: Performed inferential statistics to analyze sample data and draw conclusions about the population
- **Actionable Business Insights**: Generated specific recommendations for business stakeholders
- **Credit Behavior**: Analyzed relationships between gender, credit limits, and attrition patterns

**Business Recommendations:**
- Marketing strategies should focus on behavioral rather than demographic factors
- Credit limit management strategies can be optimized based on gender-specific patterns

###  Customer Segmentation Analysis (`CustSeg.ipynb`)

**Methodology:**
- **Data Preprocessing**: Handled missing values and outliers systematically
- **Feature Engineering**: Applied scaling and encoding transformations
- **Dimensionality Reduction**: Used PCA to reduce feature complexity
- **Clustering**: Implemented K-Means clustering with optimal cluster selection using elbow method and silhouette analysis

**Key Insights - Three Distinct Customer Segments:**

####  **Cluster 0: Young & Growing**
- **Demographics**: Younger customers with fewer months on book
- **Financial Profile**: Lower credit utilization, building credit history
- **Income**: Approximately 70% earn less than $60K annually

####  **Cluster 1: Premium & Established**
- **Demographics**: Balanced age distribution
- **Financial Profile**: Highest income group, higher credit limits, lower utilization ratios
- **Card Category**: Predominantly Silver+ cardholders
- **Gender**: Uneven gender distribution (specific patterns identified)

####  **Cluster 2: Mature & Stable**
- **Demographics**: Older customer base with longer banking relationship
- **Financial Profile**: Higher debt-to-credit ratios compared to Cluster 1
- **Income**: Similar to Cluster 0, with ~50% in lowest income bracket

**Cross-Cluster Analysis:**
- **Spending Patterns**: All clusters show similar spending behaviors
- **Credit Utilization**: Cluster 1 shows significantly lower utilization due to higher limits
- **Debt Management**: Clusters 0 and 2 carry more credit card debt relative to their limits

## 🛠️ Technical Implementation

### **Technologies Used:**
- **Python 3.x** - Primary programming language
- **Pandas & NumPy** - Data manipulation and analysis
- **Matplotlib & Seaborn** - Data visualization
- **Plotly** - Interactive visualizations
- **Scikit-learn** - Machine learning algorithms
- **Jupyter Notebooks** - Development environment

### **Key Algorithms:**
- **K-Means Clustering** - Customer segmentation
- **Principal Component Analysis (PCA)** - Dimensionality reduction
- **Statistical Analysis** - Inferential statistics for population insights

### **Data Processing Pipeline:**
1. **Data Import** - BankChurners.csv dataset
2. **Exploratory Data Analysis** - Statistical summaries and visualizations
3. **Data Cleaning** - Outlier detection and missing value treatment
4. **Feature Engineering** - Scaling, encoding, and transformation
5. **Model Development** - Clustering and prediction algorithms
6. **Results Visualization** - Interactive charts and insights

##  Business Impact

### **Actionable Strategies:**

1. **Targeted Marketing**:
   - Focus on behavioral segmentation rather than demographics
   - Develop cluster-specific marketing campaigns

2. **Retention Programs**:
   - Design age-appropriate retention strategies
   - Implement credit limit optimization for different segments

3. **Product Development**:
   - Create tailored financial products for each customer segment
   - Develop premium services for high-income Cluster 1 customers

4. **Risk Management**:
   - Monitor debt-to-credit ratios in Clusters 0 and 2
   - Implement early warning systems for churn prediction

##  Getting Started

### **Prerequisites:**
```bash
Python 3.7+
Jupyter Notebook
Required packages (see requirements.txt)
```

### **Installation:**
1. Clone the repository
2. Navigate to Customer_Segmentation folder
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

### **Running the Analysis:**
1. **Churn Analysis**: Open `Churn_Prediction/Code/Notebooks/BankChurners.ipynb`
2. **Segmentation**: Open `Customer_Segmentation/Code/Notebooks/CustSeg.ipynb`
3. Run cells sequentially to reproduce the analysis

##  Key Takeaways

- **Customer segmentation reveals three distinct behavioral groups** with different financial profiles and needs
- **Demographic factors are less predictive** than behavioral patterns for marketing effectiveness
- **Credit utilization patterns** vary significantly across customer segments
- **Age and tenure** are important factors in customer behavior and retention strategies

---
