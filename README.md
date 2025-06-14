# 📊 Customer Churn Analysis - AZWatch Subscribers

A comprehensive machine learning project analyzing customer churn patterns for AZWatch streaming service subscribers using Python and scikit-learn.

## 🎯 Project Overview

This project analyzes customer churn behavior for AZWatch subscribers to identify patterns and predict which customers are likely to cancel their subscriptions. The analysis aims to help the business understand customer engagement metrics and develop targeted retention strategies.

### Key Objectives
- Analyze customer engagement patterns and demographics
- Identify key factors influencing subscription cancellations
- Build predictive models to forecast customer churn
- Provide actionable insights for customer retention

## 📁 Project Structure

```
customer-churn-analysis/
│
├── README.md                           # Project documentation
├── customer_churn_analysis.ipynb       # Main analysis notebook
├── AZWatch_subscribers.csv             # Dataset
└── requirements.txt                    # Python dependencies (to be created)
```

## 📊 Dataset Overview

The dataset contains **1,000 AZWatch subscribers** with the following features:

| Feature | Type | Description |
|---------|------|-------------|
| `subscriber_id` | Integer | Unique customer identifier (10,000-19,976) |
| `age_group` | Categorical | Customer age demographics (3 groups) |
| `engagement_time` | Float | Average daily engagement time in hours |
| `engagement_frequency` | Integer | Number of interactions per period |
| `subscription_status` | Target | Current status: 'subscribed' or 'churned' |

### Dataset Statistics
- **Total Subscribers**: 1,000
- **Churn Rate**: 44.7% (447 churned customers)
- **Age Distribution**:
  - 35 and over: 40.8% (408 customers)
  - 18-34: 36.5% (365 customers)
  - Under 18: 22.7% (227 customers)
- **Engagement Time**: 0.22 - 16.98 hours (avg: 6.18 hours)
- **Engagement Frequency**: 0 - 45 interactions (avg: 9.98 interactions)

## 🔧 Technology Stack

- **Python 3.x**
- **Data Analysis**: pandas, numpy
- **Machine Learning**: scikit-learn
- **Visualization**: matplotlib, seaborn
- **Jupyter Notebook**: Interactive development environment

### Machine Learning Models (Planned)
- 🔍 **Logistic Regression**: Baseline classification model
- 🌳 **Decision Tree**: Interpretable rule-based model
- 🌲 **Random Forest**: Ensemble method for improved accuracy
- 🎯 **K-Means Clustering**: Customer segmentation analysis

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas scikit-learn matplotlib seaborn jupyter
```

### Running the Analysis
1. Clone this repository
2. Install required dependencies
3. Open `customer_churn_analysis.ipynb` in Jupyter Notebook
4. Run all cells to reproduce the analysis

```bash
git clone https://github.com/yourusername/customer-churn-analysis.git
cd customer-churn-analysis
jupyter notebook customer_churn_analysis.ipynb
```

## 📈 Analysis Pipeline

### 1. 📊 Exploratory Data Analysis
- Data quality assessment
- Statistical summaries
- Distribution analysis
- Correlation exploration

### 2. 🔄 Data Preprocessing
- Feature encoding for categorical variables
- Standard scaling for numerical features
- Train-test split preparation

### 3. 🤖 Model Development
- Baseline model training
- Multiple algorithm comparison
- Hyperparameter optimization
- Cross-validation evaluation

### 4. 📊 Model Evaluation
- Confusion matrix analysis
- Precision, recall, and F1-score metrics
- ROC curve and AUC analysis
- Feature importance ranking

### 5. 🎯 Customer Segmentation
- K-means clustering analysis
- Customer profile identification
- Retention strategy recommendations

## 🎯 Key Insights & Findings

> **Note**: This analysis is currently in development. Key findings and model performance metrics will be updated as the project progresses.

### Expected Outcomes
- Identification of high-risk customer segments
- Optimal engagement thresholds for retention
- Predictive model for proactive churn prevention
- Actionable recommendations for business strategy

## 📊 Visualizations

The notebook includes comprehensive visualizations:
- 📈 Engagement pattern distributions
- 🎨 Churn rate by demographic segments
- 🔄 Feature correlation heatmaps
- 📊 Model performance comparisons
- 🎯 Customer segmentation plots

## 🔍 Business Applications

### Retention Strategies
- **Early Warning System**: Identify at-risk customers before they churn
- **Targeted Campaigns**: Personalized retention offers based on customer segments
- **Engagement Optimization**: Improve features that drive customer engagement
- **Resource Allocation**: Focus retention efforts on high-value customer segments

### Success Metrics
- Reduction in overall churn rate
- Increased customer lifetime value
- Improved engagement metrics
- Enhanced customer satisfaction scores

## 📚 Future Enhancements

- [ ] Advanced feature engineering
- [ ] Deep learning models (Neural Networks)
- [ ] Time-series analysis for temporal patterns
- [ ] A/B testing framework for retention strategies
- [ ] Real-time churn prediction API
- [ ] Customer lifetime value prediction

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Contact

**Pierre-Alexandre Fumat**
- GitHub: [@pafumat](https://github.com/pafumat)
- Email: pafumat@example.com

---

*Built with ❤️ for data-driven customer success*