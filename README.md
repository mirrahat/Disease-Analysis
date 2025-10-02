
# 🏥 Diabetes Risk Assessment System

## � About This Project
This repository contains a comprehensive **Machine Learning-powered diabetes prediction system** built using Python and Streamlit. The application analyzes patient health metrics to provide accurate Type 2 diabetes risk assessments, making healthcare screening more accessible and efficient.

The system utilizes advanced data science techniques to process medical indicators and deliver personalized health insights through an intuitive web interface.

---

## ✨ Key Capabilities

**🔬 Intelligent Risk Analysis:**
- Blood glucose level evaluation
- Body Mass Index (BMI) assessment  
- Insulin resistance detection
- Age-related risk factors
- Hypertension correlation analysis
- Pregnancy history consideration

**📊 Advanced Analytics:**
- Interactive data visualizations
- Statistical model comparisons
- Performance metrics tracking
- Feature importance analysis using SHAP
- Comprehensive reporting tools

**🎨 User Experience:**
- Modern web-based interface
- Real-time prediction results
- Customizable risk thresholds
- Mobile-responsive design
- Intuitive navigation flow

---

## � Technical Implementation

**Development Stack:**
- **Backend:** Python 3.x
- **Web Framework:** Streamlit
- **ML Libraries:** scikit-learn, pandas, numpy
- **Visualization:** Plotly, Seaborn, Matplotlib  
- **Model Interpretation:** SHAP (SHapley Additive exPlanations)
- **UI Components:** Custom CSS styling

**Architecture Components:**
- `main.py` → Primary application controller
- `overview.py` → Statistical dashboard generator  
- `predict.py` → Core prediction engine
- `recommendation.py` → Personalized advice system
- `analytics.py` → Data analysis tools
- `export.py` → Report generation utilities
- `diabetes_charts.py` → Visualization components

---

## 🚀 Setup Instructions

**1. Environment Preparation**
```bash
# Navigate to project directory
cd Disease-Analysis

# Create virtual environment (recommended)
python -m venv diabetes_env
source diabetes_env/bin/activate  # On Windows: diabetes_env\Scripts\activate
```

**2. Dependency Installation**
```bash
# Install required packages
pip install -r requirements.txt
```

**3. Application Launch**
```bash
# Start the web application
streamlit run main.py
```

The application will be accessible at `http://localhost:8501`

---

## 🎯 Model Performance

**Algorithm Selection:** Gradient Boosting Classifier
- **Prediction Accuracy:** 91.2%
- **ROC-AUC Score:** 90.1% 
- **Precision:** 89.7%
- **Recall:** 88.9%

**Key Predictive Features:**
1. Plasma glucose concentration
2. Body Mass Index (BMI)
3. Patient age
4. Blood pressure readings
5. Insulin levels

---

## 💡 Use Cases

**Healthcare Applications:**
- Primary care screening programs
- Preventive medicine initiatives  
- Population health monitoring
- Clinical decision support
- Patient education tools

**Benefits:**
- Early detection capabilities
- Reduced healthcare costs
- Improved patient outcomes
- Evidence-based recommendations
- Scalable screening solutions

---

## 📱 Application Preview

The system provides an interactive dashboard where users can:
- Input health parameters through guided forms
- View real-time risk calculations
- Access detailed explanations of results
- Generate comprehensive health reports
- Receive personalized lifestyle recommendations

---
