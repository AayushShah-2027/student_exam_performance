## Project Overview
The student_exam_performance repository contains an end-to-end machine learning project focused on analyzing and predicting student exam scores based on demographic and educational factors. It demonstrates a complete ML pipeline deployable via Docker to Azure Container Registry. The project emphasizes practical deployment for real-world use.[1][2]

## Features
- Predicts student performance using factors like gender, ethnicity, parental education, lunch type, and test preparation.
- Includes data processing, model training, and evaluation steps typical for regression-based score prediction.
- Dockerized for easy containerization and cloud deployment.[3][1]

## Dataset
The project likely uses a standard student performance dataset with features such as:
- Gender (male/female)
- Race/ethnicity (groups A-E)
- Parental level of education
- Lunch (standard/free-reduced)
- Test preparation course (completed/none)
Target: Math, reading, or writing scores for regression modeling.[2][3]

## ML Pipeline
1. Data cleaning and exploratory data analysis (EDA).
2. Feature engineering and model training (e.g., regression models).
3. Model evaluation with metrics like MSE or R².
4. Containerization with Docker for production deployment.[1][2]

## Quick Start
Run these commands from the terminal in the project root:

```
docker build -t aayushshah904/mltest:latest .
docker login aayushshah904
docker push aayushshah904/mltest:latest
```

Replace credentials as needed for your Azure registry.[1]

## Technologies
- Python for ML (likely scikit-learn, pandas)
- Docker for containerization