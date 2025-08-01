📘 College Student Performance Analysis & Prediction

📌 Project Overview
This project analyzes student performance data and builds a predictive model to forecast grades and performance levels based on subject-wise marks.
It uses Python for data cleaning, visualization, and machine learning, providing actionable insights for improving academic outcomes.

🚀 Features
Data Cleaning & Preprocessing of student records

Exploratory Data Analysis (EDA) with visualizations:

Grade distribution

Attendance impact on performance

Correlation heatmap of subjects

Box plots for subject-wise marks

Decision Tree Classifier model to predict student grades (A/B/C/D/F)

Performance Level prediction (Excellent, Good, Average, Below Average, Poor)

Ready-to-use CSV dataset for 150 students

Easily adaptable for real academic data

🛠️ Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Excel/CSV for data storage

Jupyter Notebook for analysis and visualization

📂 Project Structure
college_student_performance/
│
├── data/
│   └── student_performance_150.csv
│
├── notebooks/
│   └── student_performance_analysis.ipynb
├── visuals/
│   ├── heatmap.png
│   ├── attendance_vs_total.png
│   ├── grade_distribution.png
│
└── README.md
⚙️ Installation

git clone https://github.com/your-username/college-student-performance.git
cd college-student-performance

Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
📊 Usage
Place the dataset (student_performance_150.csv) in the data/ folder.

Open the notebook:


jupyter notebook notebooks/student_performance_analysis.ipynb
Run all cells to:

Perform data analysis

Generate visualizations

Train the grade prediction model

Test predictions for new students

Example new student prediction:
predict_student_performance(85, 78, 90, 88)
Predicted Grade: B
Predicted Performance: Good


📌 Future Enhancements
Build a web app (Flask/Streamlit) for real-time grade predictions

Use additional machine learning models for improved accuracy

Deploy interactive dashboards using Power BI or Tableau
