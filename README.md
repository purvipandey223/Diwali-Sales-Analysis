# Diwali Sales Analysis

This project analyzes Diwali sales data to uncover customer purchasing behavior, identify top-performing products and regions, and provide actionable insights using Python (Jupyter Notebook).

---

## 📁 Project Structure

```
├── Diwali Sales Data.csv          # Raw dataset
├── diwali_sales_analysis.ipynb   # Jupyter Notebook with data analysis and visualization
├── README.md                     # Project documentation
├── .gitignore                    # Files and folders to ignore in version control
```

---

## 🎯 Objectives

- Clean and preprocess Diwali sales data
- Perform exploratory data analysis (EDA)
- Visualize key trends in customer demographics, product performance, and geography

---

## 📊 Dataset Description

The dataset contains sales transaction records during the Diwali festival season. Below are the key entities (columns):

| Column Name       | Description                                           |
|-------------------|-------------------------------------------------------|
| `User_ID`         | Unique identifier for each customer                   |
| `Gender`          | Gender of the customer (Male/Female)                  |
| `Age`             | Age group of the customer                             |
| `Occupation`      | Customer's profession                                 |
| `Marital_Status`  | Marital status (0 = Unmarried, 1 = Married)           |
| `State`           | State from which purchase was made                    |
| `Product_ID`      | Unique product identifier                             |
| `Category`        | Product category (e.g., Clothing, Electronics)        |
| `Amount`          | Total purchase amount spent by the customer           |

---

## 📌 Key Insights from Analysis

- **Gender-based spending**: Males made more purchases and spent more overall compared to females.
- **Top age group**: The 26-35 age group was the most active in terms of purchasing volume and spending.
- **Occupation**: Customers in IT and healthcare were among the highest spenders.
- **Marital Status**: Married customers were responsible for a higher proportion of purchases.
- **Top States**: Uttar Pradesh, Maharashtra, and Karnataka topped the charts in sales volume.
- **Product Categories**: Categories like Clothing and Electronics saw the highest traction during Diwali.

---

## 🧰 Tools & Technologies Used

- **Python** – Data cleaning and EDA (`pandas`, `matplotlib`, `seaborn`)
- **Jupyter Notebook** – Interactive coding and visualization

---

## 🚀 How to Run

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/diwali-sales-analysis.git
   cd diwali-sales-analysis
   ```

2. **Open the Notebook:**

   ```bash
   jupyter notebook diwali_sales_analysis.ipynb
   ```

---

## 📝 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---
