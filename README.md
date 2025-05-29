# Global Tech University Admissions Optimizer

## 📘 Overview

This project builds a decision-support tool to assist Global Tech University (GTU) with international graduate admissions. The model is trained on five years of applicant data to:

- Predict admission probability
- Inform scholarship decisions
- Reduce faculty review burden

## 💡 Business Questions Solved

- How do academic variables like GRE and CGPA influence admit chances?
- Can subjective features (SOP, LOR) and research background improve prediction?
- How many merit scholarships can be awarded within budget?

## 🧪 Models Used

- Multiple Linear Regression (Baseline)
- Decision Tree Regressor (Policy Interpretation)
- Random Forest Regressor (Accurate Ranking)

## ✅ Final Enhancements

- Hyperparameter tuning for Random Forest and Decision Tree
- Feature importance–based modeling (top 5)
- Multicollinearity detection and handling using VIF

## 📊 Results Summary

| Model                   | R² Score (All Features) | R² Score (Top 5 Features) |
|------------------------|-------------------------|---------------------------|
| Linear Regression       | 0.68                    | 0.64                      |
| Decision Tree Regressor| 0.73                    | 0.71                      |
| Random Forest Regressor| 0.85 (tuned)            | 0.82                      |

## 📂 Folder Structure

