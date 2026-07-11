# 📊 Data Science Project Portfolio

A comprehensive collection of data science projects showcasing exploratory data analysis, predictive modeling, and machine learning techniques. This portfolio includes three distinct projects with end-to-end analysis from data preprocessing to model evaluation.

---

## 🎯 Projects Overview

### 1. 🦠 COVID-19 Global Analysis
**Project File:** [Project_Covid_19_Analysis.ipynb](Project_Covid_19_Analysis.ipynb)

An exploratory data analysis of COVID-19 confirmed cases and deaths using the John Hopkins dataset. This project involves:
- Data aggregation and preprocessing
- Time-series visualization of confirmed cases by country
- Statistical analysis and trend identification
- Global and country-specific insights

**Dataset:** 
- `covid19_Confirmed_dataset.csv` - Confirmed cases data
- `covid19_deaths_dataset.csv` - Deaths data

**Key Techniques:** EDA, Data Aggregation, Time-Series Analysis, Data Visualization

---

### 2. 🌧️ Rainfall Prediction Using Linear Regression
**Project File:** [Project_Rainfall_Prediction.ipynb](Project_Rainfall_Prediction.ipynb)

A predictive modeling project using linear regression to forecast rainfall in Austin, Texas. This project demonstrates:
- Weather data preprocessing and feature engineering
- Linear regression model development
- Model performance evaluation
- Weather pattern analysis

**Dataset:** `austin_weather.csv` - Austin weather data with historical measurements

**Key Techniques:** Linear Regression, Feature Engineering, Model Evaluation, Data Cleaning

---

### 3. 🔬 Tumor Detection
**Project File:** [Project_Tumor_Detection (1).ipynb](Project_Tumor_Detection%20(1).ipynb)

A machine learning classification project for tumor detection with comprehensive data preprocessing and exploratory analysis. This project includes:
- Data preprocessing and feature engineering
- Exploratory data analysis
- Classification model development
- Model evaluation and performance metrics

**Dataset:** `Tumor_Detection.csv` - Tumor detection dataset with medical indicators

**Key Techniques:** Classification, Data Preprocessing, EDA, Feature Selection, Model Evaluation

---

## 📁 Project Structure

```
DataScienceProject/
├── README.md                                    # Project documentation
├── app1.py                                      # Streamlit web application
├── requirements.txt                             # Python dependencies
│
├── Project_Covid_19_Analysis.ipynb             # COVID-19 analysis notebook
├── Project_Rainfall_Prediction.ipynb           # Rainfall prediction notebook
├── Project_Tumor_Detection (1).ipynb           # Tumor detection notebook
│
├── covid19_Confirmed_dataset.csv               # COVID-19 confirmed cases data
├── covid19_deaths_dataset.csv                  # COVID-19 deaths data
├── austin_weather.csv                          # Austin weather data
├── Tumor_Detection.csv                         # Tumor detection data
└── worldwide_happiness_report.csv              # Additional dataset
```

---

## 🛠️ Technologies & Libraries

- **Python 3.x**
- **Data Processing:** pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** scikit-learn
- **Web Framework:** Streamlit
- **Jupyter Notebook**

---

## 📦 Installation & Setup

### Prerequisites
- Python 3.7 or higher
- pip or conda package manager

### 1. Clone or Download Repository
```bash
cd DataScienceProject
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Projects

#### Option A: Jupyter Notebooks (Individual Projects)
```bash
# Run individual notebooks
jupyter notebook Project_Covid_19_Analysis.ipynb
jupyter notebook Project_Rainfall_Prediction.ipynb
jupyter notebook "Project_Tumor_Detection (1).ipynb"
```

#### Option B: Streamlit Web Application (All Projects)
```bash
streamlit run app1.py
```

This launches an interactive web application showcasing all three projects with:
- Project selection via sidebar navigation
- Interactive data exploration
- Real-time visualizations
- Multi-select country comparison (COVID-19)

---

## 🚀 Live Demonstrations

### 📊 Interactive Dashboard - All Projects in One Place

Access all three projects through our unified web application:

**[🔗 View Live Dashboard](https://datascienceproject-v791.onrender.com)**

This single application provides:
- ✅ Interactive navigation between all 3 projects
- ✅ Real-time data visualizations
- ✅ Multi-select country comparison (COVID-19)
- ✅ Rainfall predictions and weather analysis
- ✅ Tumor detection analysis and insights
- ✅ Full exploratory data analysis

---

## 📊 Key Features

### COVID-19 Analysis
- ✅ Global case tracking
- ✅ Country-wise comparison
- ✅ Time-series trends
- ✅ Death statistics
- ✅ Interactive filtering

### Rainfall Prediction
- ✅ Weather data preprocessing
- ✅ Linear regression modeling
- ✅ Performance metrics visualization
- ✅ Weather pattern analysis
- ✅ Prediction accuracy evaluation

### Tumor Detection
- ✅ Medical data preprocessing
- ✅ Feature correlation analysis
- ✅ Classification model development
- ✅ Performance evaluation
- ✅ Data insights visualization

---

## 💡 How to Use

### For Learning:
1. Start with individual Jupyter notebooks to understand the analysis step-by-step
2. Review comments and documentation in each cell
3. Experiment with parameters and visualizations

### For Deployment:
1. Set up a Streamlit Cloud account
2. Connect your GitHub repository
3. Deploy `app1.py` for an interactive dashboard
4. Share the deployed link in the Demo section above

### For Modification:
1. Update datasets as needed
2. Modify parameters in notebooks or `app1.py`
3. Add new visualizations or analysis
4. Create additional project notebooks following the same structure

---

## 📈 Expected Outputs

- **COVID-19:** Line charts showing case progression, statistical summaries, data tables
- **Rainfall:** Regression plots, performance metrics, weather insights
- **Tumor Detection:** Classification reports, feature importance, confusion matrices

---

## 🤝 Contributing

Feel free to:
- Fork and enhance these projects
- Add new analysis or models
- Improve visualizations
- Expand datasets
- Create additional notebooks

---

## 📝 Notes

- Ensure all CSV files are in the same directory as the Jupyter notebooks and `app1.py`
- For Streamlit app, run from the project root directory
- Update file paths if reorganizing project structure
- Check that all dependencies are installed before running

---

## 📞 Support & Contact

For questions or issues:
- Review notebook comments and documentation
- Check dataset descriptions in respective notebooks
- Refer to library documentation (Pandas, Scikit-learn, Streamlit)

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for details.
---

**Last Updated:** June 2024

**Happy Analyzing! 🎉**
