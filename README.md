# Medical_Insurance_Premium_Predicting
---

## Overview

Medical insurance costs vary based on factors like age, BMI, smoking status, and more. This project **predicts medical insurance premiums** using a **pre-trained machine learning model**. The model is deployed using **Streamlit**, allowing users to enter their details and get an estimated premium cost.

---

## Features

✅ **User-Friendly Interface** – Built using **Streamlit**  
✅ **Pre-Trained Model** – Uses a saved `.pkl` model for predictions  
✅ **Fast Predictions** – No need for retraining, directly loads the model  
✅ **Supports Multiple Inputs** – Gender, Age, BMI, Smoking Status, Region, etc.  
✅ **Easy Deployment** – Can be hosted on **Heroku, AWS, or local server**  

---

## Dataset

The dataset used for training includes the following features:

| Feature        | Description |
|---------------|------------|
| **Age**       | Age of the insured individual |
| **Gender**    | Male/Female |
| **BMI**       | Body Mass Index |
| **Children**  | Number of dependents |
| **Smoker**    | Yes/No |
| **Region**    | Northeast, Northwest, Southeast, Southwest |
| **Charges**   | Insurance premium cost (Target Variable) |

📂 The dataset is stored as an **Excel file** and loaded using `pandas`.

---

## Technologies Used

🔹 **Programming Language**: Python  
🔹 **Machine Learning**: Decision Tree & Random Forest Regressor  
🔹 **Data Processing**: pandas, numpy, seaborn, matplotlib  
🔹 **Model Deployment**: Streamlit  
🔹 **Model Storage**: Pickle (`.pkl` file)  

---

## Installation

### 1. Clone the Repository

First, clone this repository to your local machine:
```bash
git clone https://github.com/your-username/Medical_Insurance_Premium_Predicting.git
cd Medical_Insurance_Premium_Predicting
```

### 2. Install Dependencies

Ensure you have Python installed (preferably Python 3.8+). Then, install required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn streamlit pickle5
```

---

## How to Use

### Step 1: Run the Streamlit App

After installing dependencies, start the Streamlit app:
```bash
streamlit run app.py
```

### Step 2: Enter User Details

In the **web interface**, you will be prompted to enter:  
✅ **Gender** – Male/Female  
✅ **Age** – Numeric input  
✅ **Number of Children** – Numeric input  
✅ **Smoking Status** – Yes/No  
✅ **Region** – Dropdown selection  
✅ **BMI** – Numeric input  

### Step 3: Get Predicted Insurance Premium

- Click the **Predict** button  
- The model will process inputs and return an estimated insurance premium  

---

## Project Structure

```
Medical_Insurance_Premium_Predicting/
│── data/
│   ├── insurance_data.xlsx  # Dataset
│── models/
│   ├── insurance_model.pkl  # Pre-trained model
│── app.py                   # Streamlit app for UI
│── requirements.txt          # List of dependencies
│── README.md                 # Project documentation
```

---

## Future Enhancements

🚀 **Improve Model Accuracy** – Test with other models like **XGBoost**  
☁️ **Deploy Online** – Host on **AWS, Heroku, or Streamli Cloud**  
📊 **Feature Engineering** – Improve data preprocessing and insights  

---

## License

This project is open-source and available for modification as needed.

---

## Author

👤 **Naman**   
🔗 GitHub: (https://github.com/Namaannn001/)  

---

