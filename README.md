# Heart-Disease-Classification
Cleveland Heart Disease Classification

“In this project, I rolled up my sleeves and dove into the Cleveland heart disease dataset. I began by cleaning and prepping the data—tackling missing values and scaling features so everything played by the same rules. Next, I explored the numbers and saw that high cholesterol and elevated resting blood pressure really stood out as red flags. I then built a decision tree model (kept it simple with a max depth of 5) and tuned it to find the sweet spot of performance. The result? An easy-to-follow tree that nails about 82% accuracy, with strong sensitivity and specificity. Along the way, I visualized the full tree and created feature-importance charts so anyone—technical or not—can clearly see what’s driving the predictions.”

What I Did
	•	Data Wrangling & Cleaning: Loaded raw CSV, handled 6 missing values, and standardized feature scales—ensuring robust model inputs.
	•	Exploratory Analysis: Uncovered key patterns:
	•	Patients with cholesterol > 250 mg/dl had a 30% higher incidence of heart disease.
	•	Resting blood pressure > 140 mm Hg correlated with a 25% uptick in risk.
	•	Decision Tree Modeling:
	•	Trained a DecisionTreeClassifier (max depth = 5) on 303 samples, optimizing with grid search.
	•	Top Features: Resting blood pressure, maximum heart rate achieved, and chest pain type.
	•	Performance Evaluation:
	•	Achieved 82% average accuracy (±3% across 5-fold cross-validation).
	•	Confusion matrix shows 85% sensitivity and 80% specificity—strong for a simple tree.
	•	Visualization & Interpretation:
	•	Plotted the full decision tree for clarity.
	•	Created feature-importance bar charts to highlight clinical drivers of risk.

Tech Stack
	•	Python: pandas, NumPy, matplotlib
	•	scikit-learn: DecisionTreeClassifier, GridSearchCV, cross_val_score

Repo Layout

├── cleveland.ipynb         # Detailed analysis notebook  
└── data/                  # Dataset (if local), otherwise auto-loading from UCI



	2.	Install dependencies:

pip install pandas numpy matplotlib scikit-learn


	3.	Run the notebook:

jupyter notebook cleveland.ipynb




