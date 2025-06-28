🧹 Task-2: Product Data Cleaning –Artificial Intelligence Internship Project

This notebook is the second task of my internship, focused on cleaning product-related data using Python libraries in Jupyter Notebook. The goal was to ensure the dataset is clean, consistent, and ready for analysis.

---

## 📚 Libraries Used

- **pandas** – for data manipulation  
- **numpy** – for numerical operations  
- **matplotlib** – for visualization (if needed)  
- **seaborn** – for data insights  

---

## 🧼 Cleaning Steps Performed

📥 Data Loading
- Imported required libraries  
- Loaded the raw product dataset using `read_csv()`  
- Displayed the data for initial review  

###🧾 Column-wise Cleaning

## 🛍️ `Product` Column
- Used `describe()` to understand basic stats about product entries  

## 💰 `Price` Column
- Converted values to numeric using `pd.to_numeric()`  
- Calculated the mean of the column  
- Filled missing values in the `Price` column using the calculated mean  

## 📦 `Quantity` Column
- Found the mode using `mode()[0]`  
- Filled missing values with the most frequent quantity  
- Printed the updated column to verify  

## 🌆 `City` Column
- Used `describe()` to explore the distribution and completeness of city data  

🗓️ `Purchase Date` Column
- Reviewed for format issues – no cleaning was required  

---

## ✅ Final Output

- All necessary columns were cleaned and missing data handled  
- Dataset is now consistent, numeric where needed, and free of obvious errors  
- Ready for analysis, visualization, or use in dashboards or models  

---

## 📂 Files
├── Task-2/
│ ├── Task-2.ipynb # Jupyter Notebook with step-by-step cleaning
│ └── README.md # This file

---

## 🏁 Status

✔️ Task 2 completed successfully  
⚙️ Cleaned product dataset ready for further analysis


