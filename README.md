# Tip Prediction & Customer Classification System

This project demonstrates an end-to-end **data analysis and machine learning pipeline** using the classic **Tips dataset**.  
The notebook covers data loading, exploratory data analysis (EDA), preprocessing, feature encoding, model building, and prediction.

## 📌 Project Overview

The goal of this project is to:
- Analyze customer tipping behavior
- Predict the **tip amount** using regression techniques
- Classify customers into categories based on their attributes

The project uses Python data-science libraries and is implemented in a single Jupyter Notebook.

## 📂 Files in the Repository

- `Cleaned.ipynb` – Main Jupyter Notebook containing:
  - Data loading
  - EDA & visualizations
  - Feature engineering
  - Model training
  - Prediction system

## 📊 Dataset Used

- **Tips Dataset** (loaded via `seaborn.load_dataset('tips')`)
- Contains information such as:
  - Total bill
  - Tip
  - Gender
  - Smoking status
  - Day
  - Time
  - Party size

This dataset is commonly used for learning data analysis and machine learning workflows.

## 🛠️ Technologies & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ Workflow

1. **Import Libraries & Setup**
2. **Load Dataset**
3. **Exploratory Data Analysis (EDA)**
4. **Data Cleaning & Encoding**
5. **Model Training**
   - Tip amount prediction (Regression)
   - Customer classification
6. **Prediction System**
   - Accepts new customer data
   - Outputs predicted tip and customer category

## 📈 Example Output

The system can predict:
- **Estimated tip amount**
- **Customer category** based on input features like gender, smoking status, day, time, and group size

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
