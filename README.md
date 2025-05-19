# GradientIQ

GradientIQ is a Machine Learning project that evaluates factors such as study hours, tutoring, absences for a specific semester, parental support, extracurricular activities, and sports to deliver a comprehensive **SGPA prediction**. Beyond predictions, it offers visual insights and actionable feedback, empowering students to maximize their academic efforts. 📊

---

## 💡 Key Features

- **High-Accuracy Predictions:** Delivers SGPA insights with 95% accuracy.
- **Visual Analysis:** Provides a pie chart of input data and a comparison graph showing recommended study time (min. 15 hours) vs. actual study time, helping students set study goals for success.
- **Personalized Feedback:** Offers guidance on areas for improvement, such as:
  - Increase your study time to at least 12 to 15 hours per week for a decent SGPA (study hours include college assignments, self-study, and any college-related tasks or homework).
  - Too many absences? Try to manage your schedule better.
  - Consider tutoring to boost performance.

---

## 🛠️ Technologies & Libraries Used

- Flask==3.0.3  
- numpy==2.1.2  
- pandas==2.2.3  
- matplotlib==3.9.2  
- seaborn==0.13.2  
- scikit-learn==1.5.2  
- joblib==1.4.2  
- gunicorn==21.2.0

> **Note:** `gunicorn` was not installed by default. To install it, run:

```bash
pip install gunicorn==21.2.0

git clone https://github.com/harshhrawte/GradientIQ.git
cd GradientIQ
pip install -r requirements.txt

python app.py
