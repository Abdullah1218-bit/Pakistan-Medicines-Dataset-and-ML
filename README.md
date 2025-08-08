# 🧪 Pakistan Medicines Dataset (2025)

A curated dataset of commonly available medicines in Pakistan, including detailed information such as **drug name, strength, manufacturer, form, indication, side effects, availability, age restriction, prescription status, and price**.

This dataset is intended for **healthcare analytics, data science projects, medical price prediction models**, and public health research.

---

## 📂 Dataset Overview

- **Rows**: 98+
- **Columns**: 10
- **Format**: `.csv` / `.xlsx`
- **Last Updated**: August 2025

---

## 📊 Columns Description

| Column                  | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| `Drug Name`             | Brand name of the medicine                                                  |
| `Manufacturer`          | Pharmaceutical company producing the drug                                  |
| `Strength`              | Dosage strength (e.g., 500mg or 200mg + 30mg)                               |
| `Form`                  | Physical form (Tablet, Syrup, Capsule, etc.)                                |
| `Indication`            | Conditions or symptoms the medicine is used for                             |
| `Side Effects`          | Common side effects associated with the drug                                |
| `Available In`          | Cities or regions where it is commonly available                            |
| `Age Restriction`       | Recommended minimum age for usage                                           |
| `Prescription Required`| Whether a prescription is needed to purchase (Yes/No)                        |
| `Price`                 | Price in PKR (Pakistani Rupees), typically per leaf (tablet) or per bottle  |

---

## 🧾 Sample Entries

| Drug Name     | Manufacturer | Strength        | Form   | Indication                | Price |
|---------------|--------------|------------------|--------|----------------------------|-------|
| Panadol       | GSK          | 500mg           | Tablet | Fever, mild pain          | 35    |
| Arinac Forte  | Abott        | 400mg + 60mg    | Tablet | Cold, flu, congestion     | NaN   |
| Arinac        | Abbott       | 200mg + 30mg    | N/A    | Cold, flu, nasal congestion| 65   |
| OMC-D         | Sami Pharma  | 20mg            | Tablet | Acidity, gastric issues   | 100   |

---

## 🧠 Possible Use Cases

- 💊 **Medicine price prediction models** (Regression)
- 📈 **Market trend analysis** for pharma products
- 🧬 **Drug recommendation engines**
- 🩺 **Healthcare dashboards** using Power BI / Python
- 📚 Educational projects related to public health

---

## ⚠️ Notes

- `NaN` in `Price` means price was unavailable or unconfirmed at the time of data collection.
- Always consult a healthcare professional before using any medicine listed here.

---

## 🛠️ Example (Python: Pandas Load)

```python
import pandas as pd

# Load the dataset
df = pd.read_csv("Pakistan_Medicines_Dataset.csv")

# Preview
print(df.head())
