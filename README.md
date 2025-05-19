# 🧠 Mental Health Prediction Using Machine Learning

This project aims to build a machine learning-based system to predict mental health conditions such as **anxiety**, **depression**, and **panic attacks** among students using **Decision Tree** and **Random Forest** algorithms. 
The goal is to enable early detection and help professionals take preventive actions in mental health care.

## 📌 Project Objectives

- Analyze student mental health data to identify key influencing factors.
- Build and compare machine learning models (Decision Tree, Random Forest).
- Evaluate model performance using metrics like accuracy, precision, recall, and F1-score.
- Visualize insights and model performance for clarity and decision-making.
- Provide actionable predictions for mental health status.

## 🧪 Technologies Used

- **Programming Language**: Python
- **Platform**: Google Colab
- **Libraries**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

## 🛠️ Project Structure

MentalHealthPrediction/
│
├── data/ # Dataset files (CSV)
├── notebooks/ # Jupyter/Colab notebooks
├── models/ # Trained ML models
├── screenshots/ # Model result charts & visualizations
├── mental_health_prediction.py # Main Python script (if applicable)
├── README.md # Project overview
└── requirements.txt # Python dependencies
## 🔍 Methodology

1. **Data Collection**: Student mental health dataset sourced from public surveys.
2. **Preprocessing**: Handling missing values, encoding categorical variables, and feature selection.
3. **Modeling**:
   - Decision Tree Classifier
   - Random Forest Classifier
4. **Evaluation**:
   - Accuracy: DT (64.52%), RF (87.10%)
   - Confusion Matrix & Classification Report
   - Feature Importance visualization

## 📊 Key Results

- **Random Forest** outperformed Decision Tree with a higher accuracy and better generalization.
- Important features affecting predictions include gender, GPA, marital status, and course.

## 📈 Visual Outputs

- Anxiety, Depression, Panic Attacks – by Gender & Course
- Confusion matrices for both models
- Algorithm comparison bar chart

## 🔮 Future Enhancements

- Integrate additional ML models like SVM, XGBoost, or LSTM for better accuracy.
- Include behavioral, social media, and sleep data for richer insights.
- Develop a web interface to offer real-time prediction and mental health support suggestions.



## 📚 References

Refer to the `DOCUMENT (MINI PROJECT).docx` for a full list of academic papers and resources.

---

> **Note**: This project is intended for educational and research purposes only and not for clinical diagnosis.
