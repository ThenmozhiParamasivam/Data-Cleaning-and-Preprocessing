# Data-Cleaning-and-Preprocessing

This repository contains a cleaned version of a customer dataset used for data analysis, modeling, or business intelligence. The dataset has undergone rigorous preprocessing to ensure quality, consistency, and usability for downstream tasks such as exploratory data analysis (EDA), visualization, or machine learning.

---

## 📁 Dataset Description

The original dataset included customer demographic and purchasing behavior data. The cleaning process addressed:

- 🔍 **Missing values**
- 📄 **Duplicate rows**
- 🧹 **Text standardization** (e.g., gender, marital status, country codes)
- 🗓 **Date format normalization**
- 🏷 **Column renaming** (lowercase, underscores, no spaces)
- 🔧 **Data type corrections** (e.g., `year_birth` as integer, `dt_customer` as datetime)

---

## 🧪 Cleaned Dataset

- **File Name:** `cleaned_dataset.csv`
- **Total Records:** 2,216 rows
- **Total Features:** 29 columns
- **Date Field:** `dt_customer` (converted to standard `YYYY-MM-DD` format)

---

## ✨ Sample Features

| Column             | Description                                      |
|--------------------|--------------------------------------------------|
| `year_birth`       | Year of birth of the customer                    |
| `education`        | Education level                                  |
| `marital_status`   | Marital status (standardized)                   |
| `income`           | Yearly household income                          |
| `dt_customer`      | Date when the customer joined (standardized)     |
| `recency`          | Number of days since last purchase               |
| `mnt_wines`        | Amount spent on wine products                    |
| `mnt_fruits`       | Amount spent on fruits                           |
| `mnt_meat_products`| Amount spent on meat                             |
| `num_store_purchases` | Total purchases made in store                 |
| ...                | (See full dataset for all features)              |

---

## 🛠 Tools Used

- Python (Pandas, NumPy)
- Google Colab
- GitHub

---

## 📈 Next Steps

This cleaned dataset is ready for:
- 📊 Exploratory Data Analysis (EDA)
- 🧠 Machine Learning / Predictive Modeling
- 📦 Business Dashboards (Power BI, Tableau, etc.)
- 📚 Teaching & Learning Examples

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 🙋‍♂️ Contributing

Feel free to fork this repo, use the dataset, or contribute improvements to this project.

---

## 📫 Contact

For questions or collaborations, feel free to reach out via GitHub issues or email.

