# Mini Project in Excel---List-of-Successful-Candidates
Data pre-processing and exploratory analysis using Microsoft Excel


## 📌 Project Overview

This mini project focuses on performing **data pre-processing and exploratory analysis using Microsoft Excel**. The dataset was cleaned, validated, and analyzed using Excel features such as filtering, sorting, calculated fields, and pivot tables to derive meaningful insights from election-related data.

---

# 🛠️ Data Pre-processing Steps

## 1️⃣ Removing Duplicates

Duplicate records were identified and removed to ensure data accuracy and consistency.

---

## 2️⃣ Handling Missing Values

The dataset was checked for missing or blank values in both categorical and numerical fields.

### Findings

* No blanks were found in:

  * Gender
  * Social Category
  * Party
  * Winner Vote Secured
  * RunnerUp Vote Secured
  * Margin

This confirmed that the dataset was complete and ready for analysis.

---

## 3️⃣ Standardizing Data Formats

Data types were standardized to maintain uniformity across the dataset.

### Format Adjustments

* Winner Vote Secured → Whole Number
* RunnerUp Vote Secured → Whole Number
* Margin → Whole Number
* Margin % → Decimal Number

---

## 4️⃣ Arithmetic Validation

Validation checks were performed to verify the correctness of calculated values.

### Margin Validation

```text
Margin_check = Winner Vote Secured - RunnerUp Vote Secured
```

The results matched the existing margin values, confirming data accuracy.

### Margin Percentage Validation

```text
Margin%_check =
(Margin_check / (Winner Vote Secured + RunnerUp Vote Secured)) * 100
```

The results showed expected rounded values, validating the percentage calculations.

---

# 📊 Data Analysis Techniques

## 1️⃣ Calculated Fields

Additional calculated columns were created to support deeper analysis and validation of election results.

---

## 2️⃣ Filtering & Sorting

Excel filtering and sorting techniques were used to identify important trends and insights.

### Key Findings

* Filtering by **Winner Gender** revealed that **male candidates won more elections compared to female candidates**.
* Sorting the dataset by **Margin % in descending order** helped identify candidates with the strongest victories.

### Top 2 Candidates by Margin %

1. NIMUBEN JAYANTIBHAI BAMBHANIYA (NIMUBEN BAMBHANIYA)
2. KRITI DEVI DEBBARMAN

---

## 3️⃣ Pivot Table Analysis

Pivot tables were used to summarize and analyze election data efficiently, enabling better comparison across categories and candidates.

---

# 📌 Conclusion

This project demonstrates the use of **Excel for data cleaning, validation, and analysis**. Through preprocessing techniques and analytical methods such as filtering, sorting, and pivot tables, meaningful insights were extracted from the dataset, improving data reliability and supporting informed decision-making.
