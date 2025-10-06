
# Detecting Mental Stress and Risk of Suicide Attempts in Students

This project aims to identify students at risk of mental stress and potential suicide attempts using survey response data and machine learning.

## 📌 Objective
To decrease suicide rates among students by predicting at-risk individuals and providing timely interventions like counseling.

## 💻 Technologies Used
- Python
- Pandas, Sklearn, Matplotlib, Seaborn
- SQL (for pre-processing if applicable)
- GitHub for version control

## 🧠 Model
A Random Forest Classifier is trained to detect high-risk students based on input features like:
- Anxiety level
- Sleep patterns
- Academic performance
- Social interactions
- Counseling history

## 📊 Output
- Accuracy score and classification report
- Feature importance chart to understand the most influential factors

## 📂 How to Run
1. Clone the repo
2. Add your `student_responses.csv` dataset
3. Run:
```bash
python mental_stress_risk_detection.py
```

## 📎 Dataset
You can simulate or use a real anonymized dataset with features such as:
- AnxietyScore, SleepHours, AcademicPressure, SocialSupport, CounselingBefore, AtRisk

## 🙌 Outcome
A list of predicted students at risk, along with insights to help educational institutions take proactive measures.
