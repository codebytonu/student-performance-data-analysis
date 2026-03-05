# Student Performance Data Analysis 📊

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a student performance dataset to understand the factors affecting students' final grades.

The analysis focuses on variables such as study time, absences, parental education, alcohol consumption, and past academic failures to identify patterns that influence student performance.

The project demonstrates how Python can be used to clean, analyze, and visualize real-world data.

---

## Objectives
The main objectives of this project are:

- Analyze factors affecting student academic performance
- Explore relationships between study habits and final grades
- Identify high-performing and low-performing students
- Detect students who may be academically at risk
- Visualize insights using data visualization techniques

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Dataset Information

The dataset contains student academic and personal information including:

- Study time
- Absences
- Past failures
- Mother's education level
- Alcohol consumption
- First period grade (G1)
- Second period grade (G2)
- Final grade (G3)

These variables are used to analyze patterns and relationships affecting student performance.

---

## Project Workflow

### 1. Data Loading
The dataset is loaded using Pandas and stored in a DataFrame for analysis.

### 2. Data Exploration
Initial exploration is performed using:

- dataset shape
- column inspection
- info()
- statistical summary

### 3. Data Cleaning
The dataset is checked for missing values and inconsistencies.

### 4. Exploratory Data Analysis (EDA)
Multiple analyses were performed including:

- Distribution of final grades
- Study time vs final grades
- Absences vs final grades
- Mother's education vs student performance
- Alcohol consumption vs grades
- Past failures vs final grade

### 5. Feature Engineering
A new feature called **Progress** was created:

Progress = G3 - G2

This measures improvement in student performance.

### 6. Correlation Analysis
Correlation between key variables was analyzed to identify relationships influencing student performance.

### 7. Risk Identification
Students were categorized as **At Risk** based on factors such as:

- High absences
- Previous failures
- High alcohol consumption

### 8. Top and Lowest Performing Students
The dataset was sorted to identify:

- Top 10 highest-performing students
- Top 10 lowest-performing students

---

## Key Insights

Some important insights from the analysis include:

- Students with higher study time generally achieve better grades.
- High absenteeism negatively impacts student performance.
- Previous academic failures strongly correlate with lower final grades.
- Lifestyle factors such as alcohol consumption may influence academic results.

---

## Example Code

```python
top_students = df.sort_values("G3", ascending=False).head(10)
lowest_students = df.sort_values("G3", ascending=True).head(10)
```

---

## Visualizations

The project includes multiple visualizations such as:

- Histogram of final grades
- Bar charts
- Scatter plots
- Correlation heatmaps

These visualizations help identify patterns in the dataset.

---

## Project Structure

```
student-performance-data-analysis
│
├── student_dataanalyse.ipynb
├── student_dataset.csv
└── README.md
```

---

## Conclusion

This project demonstrates how exploratory data analysis can uncover meaningful insights from educational datasets.

Using Python and data visualization tools, we can identify key factors affecting student academic performance and support data-driven decision making in education.

---

## Author

Alhin Arabia Tonu

Digital Marketer | Data Analyst Learner | CSE Student

GitHub: https://github.com/
