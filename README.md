# SmartGrade Predictor

## Overview
The **SmartGrade Predictor** is a demonstration machine learning project designed to predict factors influencing student academic performance using various classification algorithms. The project leverages a structured CSV dataset encompassing diverse attributes related to students' behaviors and demographics.

This project aims primarily at:
- Providing practical experience in applying different classifiers.
- Understanding the impact of various factors on student grades.
- Interpreting model performance through visualizations.

## Dataset
The dataset (`AI-Data.csv`) comprises several student-specific features, including:
- Demographic information (nationality, gender, grade level).
- Behavioral metrics (number of raised hands, attendance, study hours).
- Academic indicators (semester details, participation in discussions).

A sample of the dataset includes:
| gender | NationalITy | PlaceofBirth | StageID    | GradeID | SectionID | Topic | Semester | Relation | raisedhands | VisITedResources | AnnouncementsView | Discussion | ParentAnsweringSurvey | ParentschoolSatisfaction | StudentAbsenceDays | Class |
|--------|-------------|--------------|------------|---------|-----------|-------|----------|----------|-------------|------------------|-------------------|------------|-----------------------|--------------------------|--------------------|-------|
| M      | KW          | KuwaIT       | lowerlevel | G-04    | A         | IT    | F        | Father   | 15          | 16               | 2                 | 20         | Yes                   | Good                     | Under-7            | M     |

## Classifiers Implemented
The project includes the following classifiers:
- Decision Tree Classifier
- Random Forest Classifier
- Perceptron (Linear Model)
- Logistic Regression (Linear Model)
- Neural Network (MLP Classifier)

## Visualization and Results
The project includes interactive visualization options, offering insights into the data through:
- Count Plots (Class distribution across factors such as Semester, Gender, Nationality, Grade, Section, Topic, Stage, and Absence days)
- Confusion Matrix and detailed classification reports for performance evaluation

## Project Structure
```
SmartGrade Predictor/
├── AI-Data.csv
├── predictor.py
└── README.md
```

## Dependencies
- Python (3.x)
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
Run the predictor script using:
```bash
python predictor.py
```

