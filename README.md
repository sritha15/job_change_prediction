# Job Change Prediction - Complete ML Lifecycle

A comprehensive machine learning project that predicts whether a data science professional will change jobs, implementing the complete ML lifecycle from data exploration to model deployment.

## 📊 Project Overview

This project analyzes job change patterns among data science professionals using advanced machine learning techniques. The analysis includes:

- **Comprehensive EDA** with 40+ visualizations
- **Advanced Feature Engineering** with encoding strategies
- **Class Imbalance Handling** using SMOTE and undersampling
- **Multiple ML Models** comparison with cross-validation
- **Model Interpretability** using SHAP analysis
- **Performance Optimization** with hyperparameter tuning

## 📁 Project Structure

```
job_change_prediction/
├── Complete_ML_Lifecycle_Job_Change_Prediction.ipynb  # Main analysis notebook
├── requirements.txt                                   # Python dependencies
├── README.md                                         # Project documentation
├── ML_Job_Change_Report.pdf                          # Detailed project report
├── Sadaora_MachineLearningAsessment.pdf             # Assessment document
└── Datasets/
    ├── aug_train.csv                                 # Training dataset
    ├── aug_test.csv                                  # Test dataset
    └── sample_submission.csv                         # Sample submission format
```

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Git (for cloning the repository)

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sritha15/job_change_prediction.git
   cd job_change_prediction
   ```

2. **Create a virtual environment (recommended):**
   ```bash
   # Using venv
   python -m venv job_change_env
   
   # Activate the environment
   # On Windows:
   job_change_env\Scripts\activate
   # On macOS/Linux:
   source job_change_env/bin/activate
   ```

3. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

5. **Open and run the main notebook:**
   - Navigate to `Complete_ML_Lifecycle_Job_Change_Prediction.ipynb`
   - Run all cells sequentially (Cell → Run All)

## 📋 Requirements.txt Dependencies

The project uses the following key libraries:

- **Data Manipulation:** pandas, numpy
- **Visualization:** matplotlib, seaborn, plotly
- **Machine Learning:** scikit-learn, imbalanced-learn
- **Model Interpretability:** shap
- **Statistical Analysis:** scipy, statsmodels
- **Development:** jupyter, ipython

For the complete list with versions, see `requirements.txt`.

## 🔧 Execution Instructions

### Step-by-Step Execution

1. **Environment Setup:**
   ```bash
   # Ensure you're in the project directory
   pwd  # Should show .../job_change_prediction
   
   # Verify Python version
   python --version  # Should be 3.8+
   
   # Install dependencies
   pip install -r requirements.txt
   ```

2. **Data Verification:**
   ```bash
   # Check if datasets are present
   ls Datasets/
   # Should show: aug_train.csv, aug_test.csv, sample_submission.csv
   ```

3. **Run the Analysis:**
   ```bash
   # Start Jupyter
   jupyter notebook
   
   # Alternative: Use JupyterLab
   jupyter lab
   ```

4. **Execute Notebook Sections:**
   - **Data Loading & EDA:** Cells 1-20
   - **Feature Engineering:** Cells 21-35
   - **Model Training:** Cells 36-50
   - **SHAP Analysis:** Cells 51-60

### Memory Requirements

- **Minimum RAM:** 8GB
- **Recommended RAM:** 16GB or higher
- **Storage:** At least 500MB free space

### Expected Runtime

- **Complete notebook execution:** 15-30 minutes
- **EDA section:** 5-10 minutes
- **Model training:** 5-15 minutes
- **SHAP analysis:** 5-10 minutes

## 📈 Key Features

### Machine Learning Models Implemented
- Random Forest Classifier
- Gradient Boosting Classifier
- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors

### Advanced Techniques
- **Cross-validation** with StratifiedKFold
- **Hyperparameter tuning** with GridSearchCV
- **Class imbalance handling** with SMOTE and Random Undersampling
- **Feature scaling** for distance-based models
- **SHAP interpretability** analysis

### Comprehensive Evaluation Metrics
- ROC-AUC Score
- F1-Score
- Precision & Recall
- Accuracy
- Confusion Matrix Analysis

## 📊 Expected Outputs

Running the complete notebook will generate:

1. **40+ Visualizations** including:
   - Distribution plots
   - Correlation matrices
   - Feature importance plots
   - SHAP summary plots

2. **Model Performance Reports** with:
   - Cross-validation scores
   - Best model identification
   - Performance comparison tables

3. **Feature Analysis** including:
   - Correlation analysis
   - Feature importance rankings
   - SHAP interpretability insights

## 🛠️ Troubleshooting

### Common Issues & Solutions

1. **Import Errors:**
   ```bash
   # Reinstall requirements
   pip install --upgrade -r requirements.txt
   ```

2. **Memory Issues:**
   ```bash
   # Reduce dataset size for testing
   # Or increase virtual memory/swap space
   ```

3. **Jupyter Kernel Issues:**
   ```bash
   # Restart kernel
   # Kernel → Restart & Clear Output
   ```

4. **Package Version Conflicts:**
   ```bash
   # Create fresh virtual environment
   python -m venv fresh_env
   source fresh_env/bin/activate  # or fresh_env\Scripts\activate on Windows
   pip install -r requirements.txt
   ```

## 📚 Additional Resources

- **Detailed Report:** See `ML_Job_Change_Report.pdf` for comprehensive analysis
- **Assessment Document:** `Sadaora_MachineLearningAsessment.pdf`
- **Jupyter Documentation:** [https://jupyter.org/documentation](https://jupyter.org/documentation)
- **Scikit-learn Documentation:** [https://scikit-learn.org/](https://scikit-learn.org/)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is for educational and assessment purposes.

## 📧 Contact

For questions or issues, please open an issue in this repository.

---

**Happy Analyzing! 🚀** 