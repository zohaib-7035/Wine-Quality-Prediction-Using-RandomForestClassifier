

# 🍷 Wine Quality Prediction  

This project uses **machine learning** to predict the quality of wine based on its chemical properties. A **Random Forest Classifier** is trained to classify wine as either **good quality** or **bad quality** based on a given dataset.  

## 📌 Features  
- Exploratory Data Analysis (EDA) using **Seaborn** and **Matplotlib**  
- Data preprocessing and feature engineering  
- Machine learning model training using **Random Forest Classifier**  
- Model evaluation using **accuracy score**  
- Prediction of wine quality based on user-input chemical properties  

## 📂 Dataset  
The dataset used for this project is **wine.csv**, which contains various chemical attributes of wine, including:  
- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  
- Quality (Target Variable)  


## 🎯 Model Accuracy  
The **Random Forest Classifier** achieves an accuracy of approximately **X%** on the test set.  

## 🛠 Technologies Used  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-Learn  
- Jupyter Notebook / Google Colab  

## 📌 Example Prediction  
```python
input_data = (7.5,0.5,0.36,6.1,0.071,17.0,102.0,0.9978,3.35,0.8,10.5)
prediction = model.predict(np.asarray(input_data).reshape(1, -1))
print("Good Quality" if prediction == 1 else "Bad Quality")


