# Student Performance Analysis

## Overview

This project aims to analyze factors that influence students' academic performance using a comprehensive dataset. The analysis includes data cleaning, exploratory data analysis (EDA), and predictive modeling to identify key variables affecting students' exam scores. The dataset contains various attributes related to student behavior, demographics, and academic environment, which can help understand the correlation between these factors and student success.

## Dataset Description

The dataset contains **6607** entries with **20** columns, representing various factors that might influence students' academic performance. Here’s a brief description of the columns:

| Column                      | Description                                                  | Type    |
|-----------------------------|--------------------------------------------------------------|---------|
| `Hours_Studied`             | Number of hours a student studies per week                   | Integer |
| `Attendance`                | Attendance percentage of the student                         | Integer |
| `Parental_Involvement`      | Level of involvement by parents in the student’s academics   | Categorical (Low/Medium/High) |
| `Access_to_Resources`       | Access to learning resources (e.g., internet, books)         | Categorical (Low/Medium/High) |
| `Extracurricular_Activities`| Participation in extracurricular activities (Yes/No)         | Categorical |
| `Sleep_Hours`               | Average sleep hours per day                                  | Integer |
| `Previous_Scores`           | Previous academic scores (out of 100)                        | Integer |
| `Motivation_Level`          | Level of student motivation                                  | Categorical (Low/Medium/High) |
| `Internet_Access`           | Availability of internet access (Yes/No)                     | Categorical |
| `Tutoring_Sessions`         | Number of additional tutoring sessions attended              | Integer |
| `Family_Income`             | Family income bracket                                       | Categorical (Low/Medium/High) |
| `Teacher_Quality`           | Quality of teaching as perceived by students                 | Categorical |
| `School_Type`               | Type of school (Public/Private)                              | Categorical |
| `Peer_Influence`            | Influence of peers on the student                            | Categorical (Positive/Neutral/Negative) |
| `Physical_Activity`         | Frequency of physical activity sessions per week             | Integer |
| `Learning_Disabilities`     | Whether the student has a learning disability (Yes/No)       | Categorical |
| `Parental_Education_Level`  | Highest level of education attained by the student's parents | Categorical |
| `Distance_from_Home`        | Distance from school to home (Near/Moderate/Far)             | Categorical |
| `Gender`                    | Gender of the student (Male/Female)                          | Categorical |
| `Exam_Score`                | Final exam score (out of 100)                                | Integer |

## Analysis and Methodology

The analysis follows these key steps:

1. **Data Cleaning**: Addressing missing values, checking for outliers, and ensuring data consistency.
2. **Exploratory Data Analysis (EDA)**: Understanding relationships between features using visualizations like histograms, scatter plots, and heatmaps.
3. **Feature Engineering**: Creating new features that may enhance the predictive model's performance.
4. **Model Building**: Implementing regression models to predict `Exam_Score` based on the provided features.
5. **Model Evaluation**: Evaluating the model using metrics such as R-squared, mean squared error (MSE), and feature importance.

## Requirements

To run the analysis and replicate the results, you need the following dependencies:

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install the required packages using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. **Clone the Repository**: Clone the project repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/student-performance-analysis.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd student-performance-analysis
   ```

3. **Run the Jupyter Notebook**:

   ```bash
   jupyter notebook student-performance.ipynb
   ```

4. **Follow the Analysis**: Open the notebook and run the cells sequentially to execute the data analysis and modeling steps.

## Results

- The analysis identifies key factors like **study hours**, **parental involvement**, **previous scores**, and **teacher quality** as significant determinants of student performance.
- Predictive models can estimate student scores with reasonable accuracy, providing insights for educators and policymakers.

## Sample Data

Here’s a glimpse of the dataset:

| Hours_Studied | Attendance | Parental_Involvement | Access_to_Resources | Exam_Score |
|---------------|------------|---------------------|---------------------|------------|
| 23            | 84         | Low                 | High                | 67         |
| 19            | 64         | Low                 | Medium              | 61         |
| 24            | 98         | Medium              | Medium              | 74         |
| 29            | 89         | Low                 | Medium              | 71         |
| 19            | 92         | Medium              | Medium              | 70         |

## Contributing

Contributions are welcome! Feel free to fork this repository, improve the code or analysis, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the open-source community for the tools and libraries used in this project.
- If you use this dataset or analysis in your research, please credit the authors appropriately.

---
