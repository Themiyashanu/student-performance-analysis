# student-performance-analysis
Educational analytics project identifying factors that influence student academic success. Analyzes 1000+ student records to uncover insights about gender differences, parental education impact, and test preparation effectiveness. Provides actionable recommendations for educators and policymakers using data-driven approaches.

# 📊 Student Performance Analysis

A comprehensive data science project analyzing factors that influence student academic performance using machine learning techniques.


## 🎯 Project Overview

This project analyzes student performance data to identify key factors that influence academic success. Using exploratory data analysis and machine learning models, we uncover insights about how various demographic and socio-economic factors impact student scores.

## 📁 Repository Structure

```
student-performance-analysis/
├── README.md                           # Project documentation
├── Student_Performance_Analysis.ipynb  # Main Jupyter notebook
├── data/
│   └── student_performance_processed.csv  # Processed dataset
├── results/
│   ├── student_performance_analysis.png   # Main visualizations
│   ├── model_performance.png             # Model comparison
│   ├── feature_importance.csv            # Feature importance data
│   ├── model_results.csv                 # Model performance metrics
│   └── project_summary.txt               # Executive summary
└── requirements.txt                    # Python dependencies
```

## 🔍 Key Features

- **Comprehensive EDA**: Visual analysis of student performance patterns
- **Statistical Insights**: Deep dive into factors affecting academic success
- **Machine Learning**: Predictive models using Linear Regression and Random Forest
- **Feature Analysis**: Identification of most important performance predictors
- **Interactive Visualizations**: Clear, publication-ready charts and graphs

## 📊 Dataset Information

The dataset contains **1000+ student records** with the following features:
- **Demographics**: Gender, race/ethnicity
- **Socio-economic**: Parental education, lunch type
- **Academic**: Math, reading, and writing scores
- **Preparation**: Test preparation course completion

## 🎨 Key Visualizations

### 1. Score Distributions
Distribution analysis of math, reading, and writing scores across the student population.

### 2. Gender Performance Analysis
Comparative analysis showing performance differences between male and female students.

### 3. Parental Education Impact
Correlation between parental education levels and student academic performance.

### 4. Test Preparation Effectiveness
Analysis of how test preparation courses affect student scores.

## 🤖 Machine Learning Models

### Models Implemented:
1. **Linear Regression**: Baseline model for performance prediction
2. **Random Forest**: Advanced ensemble method for better accuracy

### Performance Metrics:
- **R² Score**: Measures model accuracy
- **Mean Squared Error**: Prediction error measurement
- **Feature Importance**: Identifies key performance predictors

## 📈 Key Findings

1. **Strong Correlation**: Reading and writing scores show high correlation (>0.8)
2. **Gender Differences**: Slight variations in performance across different subjects
3. **Education Impact**: Parental education level significantly affects student performance
4. **Preparation Benefits**: Students who completed test preparation courses show improved scores
5. **Socio-economic Factors**: Lunch type (standard vs. free/reduced) indicates performance patterns

## 🚀 Quick Start

### Option 1: Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the notebook file
3. Run all cells sequentially
4. Download generated files

### Option 2: Local Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/student-performance-analysis.git
cd student-performance-analysis

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook Student_Performance_Analysis.ipynb
```

## 📦 Dependencies

```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=1.0.0
jupyter>=1.0.0
```

## 📊 Sample Results

### Model Performance
- **Linear Regression R²**: 0.875
- **Random Forest R²**: 0.912
- **Best Performing Model**: Random Forest

### Top 5 Important Features
1. Reading Score (0.489)
2. Math Score (0.387)
3. Parental Education (0.089)
4. Test Preparation (0.067)
5. Gender (0.045)

## 🎯 Business Applications

This analysis can help:
- **Educational Institutions**: Identify at-risk students early
- **Policy Makers**: Understand factors affecting educational outcomes
- **Parents**: Make informed decisions about test preparation
- **Researchers**: Build upon existing educational research

## 🔄 Future Enhancements

- [ ] Add more advanced ML models (XGBoost, Neural Networks)
- [ ] Implement cross-validation for better model validation
- [ ] Add interactive dashboards using Plotly/Dash
- [ ] Include time-series analysis for longitudinal data
- [ ] Develop web application for real-time predictions

## 📝 Data Source

Dataset sourced from publicly available educational performance data. All data has been anonymized and is used for educational purposes only.

## 👤 Author

- Email: themiya.shanu,tt@gmail.com



## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## ⭐ Show Your Support

If you found this project helpful, please give it a ⭐ on GitHub!

---

**Made with ❤️ and Python**
