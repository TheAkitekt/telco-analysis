This project is a practical analysis of a Telco customer churn dataset. My goal was to approach it the same way I would in a real data role: clean the data, understand what drives churn, validate assumptions with visuals and models, and produce something useful rather than just exploratory charts.

What I Did
<img width="968" height="644" alt="Screenshot 2025-11-24 230702" src="https://github.com/user-attachments/assets/86f9ab1f-8398-438b-b39b-7f33e8fa0eb9" />
<img width="806" height="634" alt="Screenshot 2025-11-24 230631" src="https://github.com/user-attachments/assets/21738c5a-1926-463a-9cb1-16ea31e659d8" />
<img width="728" height="642" alt="Screenshot 2025-11-24 230915" src="https://github.com/user-attachments/assets/10f8ea1d-8faa-41ef-9f61-912dea6cbd19" />
<img width="718" height="644" alt="Screenshot 2025-11-24 230852" src="https://github.com/user-attachments/assets/9cb2686f-c710-4167-a97d-1ed2c6db5b6f" />
<img width="914" height="642" alt="Screenshot 2025-11-24 230827" src="https://github.com/user-attachments/assets/d6ab1a87-cc63-4ded-bbbe-729e9b615363" />
<img width="924" height="642" alt="Screenshot 2025-11-24 230739" src="https://github.com/user-attachments/assets/c06371a5-c697-4429-a7a9-d9c48c183600" />


Cleaned and prepared the dataset (fixed data types, handled missing values).
Looked for patterns in churn based on tenure, contract type, and charges.
Explored correlations and extracted the strongest churn signals.
Built two baseline predictive models (Logistic Regression + Random Forest).
Identified the most important features influencing churn.
Created a simple short-term churn forecast by tenure to show trend thinking.

What I Found

Contract type is one of the clearest indicators of churn
Higher monthly charges tend to correlate with higher churn risk.
Longer tenure customers churn less, which the forecast supports.
Support related features (like Tech Support) also play a strong role in customer retention.

Why This Project Matters

This notebook reflects how I approach business problems:
Start with data quality
Focus on drivers and interpretability
Use models to support insights not replace them
Present information clearly and with business value in mind

