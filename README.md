
# FastAPI diabetes predicting Machine Learning application in Render

This project demonstrates the deployment of a machine learning model for predicting diabetes using FastAPI. The API is deployed on Render, a free hosting platform, and is accessible via a simple endpoint for predictions.


## Used technologys 

 - python
 - FastAPI
 - render
 - scikit-learn
 - Uvicorn


## Model Details

The machine learning model was developed using the scikit-learn and trained on the free kaagle data set

## Features Used 

 - Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age
## project documentation
for the get full idea about this projrct and devolopment read this documentat 
-[Full document how to deploy and what is this project](https://medium.com/@nimantha1020/how-to-deploy-a-fastapi-diabetes-predicting-machine-learning-application-in-render-39b75a7f3fad)


## Use API

- [API link](https://fastapi-itbin-2110-0159.onrender.com/)
- [API prediction](https://fastapi-itbin-2110-0159.onrender.com/docs)

## API Endpoints

#### Input

```{
  "pregnancies": 2,
  "glucose": 120,
  "blood_pressure": 70,
  "skin_thickness": 30,
  "insulin": 80,
  "bmi": 28.5,
  "diabetes_pedigree_function": 0.5,
  "age": 33
}

```
#### Input

```
The person is not Diabetic

