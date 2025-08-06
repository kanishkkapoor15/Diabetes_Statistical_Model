🩺📊 From EDA to XGBoost: A Complete Data Science Project on Predicting Diabetes

Over the last few weeks, I worked on a comprehensive healthcare data science project — focused not just on building a machine learning model, but on deeply understanding the why behind the what through the lens of statistics. Here’s a look at the end-to-end journey:

⸻
<img width="727" height="582" alt="Screenshot 2025-08-05 at 6 42 19 PM" src="https://github.com/user-attachments/assets/5388096e-3bf0-4475-be35-2140bdef4d1a" />


🔍 Stage 1: Exploratory Data Analysis (EDA)

We began by exploring patterns in a real-world public health dataset containing over 250,000 records. Key observations included:
	•	A clear imbalance in the diabetes-positive vs negative classes.
	•	Strong visible trends in age, BMI, and general health indicators.
 
<img width="1342" height="444" alt="Screenshot 2025-08-05 at 6 42 36 PM" src="https://github.com/user-attachments/assets/0357814a-b2b4-40fb-bbc3-6e4517edac40" />

⸻

🎲 Stage 2: Probability Application

We applied core probability concepts to understand the relationships between features like HighBP, HighChol, and BMI, and their likelihood of indicating diabetes. Conditional probabilities helped us intuitively frame risk factors.

⸻

📈 Stage 3: Inferential Statistics & Hypothesis Testing

Using:
	•	t-tests (for continuous features like BMI),
	•	chi-square tests (for categorical features like HighBP, Smoker),
We statistically validated that several features had a significant impact on diabetes status (p-values < 0.05).

⸻<img width="673" height="548" alt="Screenshot 2025-08-05 at 7 21 46 PM" src="https://github.com/user-attachments/assets/b9554550-575c-4eea-9ed8-a5fc8a8455a9" />


📊 Stage 4: Regression Analysis

We ran a Logistic Regression to estimate the certainty of each predictor’s impact:
	•	HighBP, HighChol, and BMI had strong positive coefficients.
	•	Fruits and Veggies had negative coefficients (protective factors).
This gave us both feature importance and directionality of impact.

⸻
<img width="676" height="494" alt="Screenshot 2025-08-06 at 5 38 00 PM" src="https://github.com/user-attachments/assets/7cf971ed-7d65-463c-8469-2d0db0bf2173" />

🤖 Stage 5: Predictive Modeling

We experimented with traditional and advanced classifiers and finally ran:
✅ XGBoost Classifier
Achieved 86% accuracy on the test set.

But here’s the real learning:
	•	The model perfectly predicted the negative class (non-diabetics) but struggled with positive cases (diabetics).
	•	BMI emerged as the most important feature, highlighting the role of weight and lifestyle in diabetes prediction.

⸻
<img width="594" height="316" alt="Screenshot 2025-08-06 at 11 58 25 PM" src="https://github.com/user-attachments/assets/1201e7f5-4f65-4d02-a601-180ec5153c66" />


🧠 Key Takeaways:
	•	Statistical foundations are critical — not just for understanding data, but for explaining models.
	•	Interpretability matters: Logistic regression helped us gain trust before diving into black-box models like XGBoost.
	•	Even high accuracy doesn’t always mean good predictions for minority classes — handling imbalance is essential.

⸻
<img width="712" height="569" alt="Screenshot 2025-08-07 at 12 08 17 AM" src="https://github.com/user-attachments/assets/e5285646-de44-4af6-9269-e86626fc092b" />

🚀 This project was a great deep dive into applying statistics, ML, and interpretability to solve real-world healthcare problems.

💬 Would love to hear how others are combining statistical thinking with machine learning in their projects!

#DataScience #MachineLearning #Statistics #HealthcareAnalytics #XGBoost #EDA #PredictiveModeling #LogisticRegression #ChiSquare #HypothesisTesting
