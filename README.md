# Students Performance Prediction

## Project Overview
This project aims to predict students' performance in three subjects: Math, Reading, and Writing. Using a dataset of students' demographic and background information, we apply machine learning techniques to forecast their scores based on various factors.

## Dataset
The dataset used in this project is the **StudentsPerformance.csv** file, containing the following columns:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

## Project Structure
- **Data Preprocessing**: Handle missing values and encode categorical variables.
- **Exploratory Data Analysis (EDA)**: Visualize score distributions and relationships between features.
- **Model Training**: Train a multivariate linear regression model to predict the scores.
- **Evaluation**: Measure the model performance using RMSE and R² scores.
- **Visualization**: Plot actual vs. predicted scores to evaluate model accuracy.

## Installation
Make sure you have the required libraries installed:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Clone the repository:
```
git clone https://github.com/yourusername/students-performance-prediction.git
```
2. Navigate to the project directory:
```
cd students-performance-prediction
```
3. Run the script:
```
python students_performance_project.py
```

## Results
The model provides predictions for math, reading, and writing scores with the following evaluation metrics:
- RMSE and R² for each subject.
- Graphical comparison between actual and predicted scores.

## Contributions
Feel free to open issues or submit pull requests if you want to contribute to the project!

## License
This project is licensed under the MIT License.

