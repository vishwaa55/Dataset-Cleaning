# Dataset-Cleaning
This project is about working on a dirty dataset inorder to handle improper values and formats, it finally returns a new .csv file which is clean and ready to be used to train an AI model.

# ☕ Cafe Sales Data Cleaning

This project focuses on **cleaning and preprocessing a café sales dataset** using **Python and Pandas**.

---

## 📊 Dataset
The dataset contains café transaction records with the following columns:

- Transaction ID  
- Item  
- Quantity  
- Price Per Unit  
- Total Spent  
- Transaction Date  
- Location  
- Payment Method  

---

## 🧹 What I Did
- Handled missing values (`NaN`, `ERROR`, `UNKNOWN`)
- Fixed incorrect data types
- Parsed and cleaned date values
- Removed duplicate rows
- Corrected logical errors using  
  `Total Spent = Quantity × Price Per Unit`
- Filled missing values using item–price relationships
- Dropped rows with insufficient or invalid data
- Standardized text values (Item names)

---

## 📁 Output
- **`cleaned_cafe_sales.csv`**  
A cleaned version of the dataset, ready for analysis.

---

## 🗂 Dataset Source
The dataset was provided as a **raw, messy café sales CSV file** for learning and practice purposes.  
It was not collected manually and is used only for **educational data cleaning and preprocessing**.

---

## 🛠 Tools Used
- Python 🐍  
- Pandas  
- NumPy  
- Google Colab  

---

## ✍️ Author
Created as a practice project to understand **data cleaning and preprocessing using Pandas**.

---

## 📈 Monthly Sales Trend

This visualization shows how total café sales vary across different months, helping identify seasonal patterns and high-activity periods throughout the year.

<img width="630" height="470" alt="Monthly Sales Trend" src="https://github.com/user-attachments/assets/095f5406-25ae-4dd4-9340-6864362cc39d" />

---

## 🍰 Revenue Share by Each Item

This chart highlights the contribution of each item to the total revenue, making it easy to see which products generate the most sales.

<img width="486" height="470" alt="Revenue Share by Item" src="https://github.com/user-attachments/assets/0b0c4c04-69d5-4044-b61b-7c22c57ca795" />


