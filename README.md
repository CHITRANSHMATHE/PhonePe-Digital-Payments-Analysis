#  PhonePe Digital Payments Analysis

##  Overview

This project analyzes transaction, user behavior, device usage, and demographic data from PhonePe across Indian states and districts.

The objective is to extract meaningful insights into:

* Transaction growth trends
* User behavior patterns
* Device usage distribution
* Demographic influence on digital payments
* Data consistency across hierarchical levels

---

##  Dataset Description

The analysis is based on multiple datasets:

* **State_Txn and Users** → Transactions, Amount, Users, App Opens
* **State_TxnSplit** → Transaction type breakdown
* **State_DeviceData** → Device brand usage
* **District_Txn and Users** → District-level metrics
* **District Demographics** → Population, Area, Density

---

##  Project Workflow

### 1. Data Loading & Understanding

* Imported multi-sheet Excel dataset
* Explored structure, data types, and completeness

### 2. Exploratory Data Analysis (EDA)

* Identified trends in transactions and app usage
* Compared state-wise performance
* Analyzed transaction type distribution

### 3. Data Quality Checks

* Checked missing values and inconsistencies
* Validated district ↔ state aggregation
* Identified discrepancies in transaction and amount

### 4. Data Merging & Advanced Analysis

* Combined transaction and demographic datasets
* Calculated:

  * Average Transaction Value (correct weighted method)
  * Device usage ratios
  * Correlation between population density and transactions

### 5. Data Visualization

* Line plots for time trends
* Bar charts for comparisons
* Pie charts for distribution
* Multi-state comparisons using seaborn

### 6. Insights & Conclusions

* Extracted behavioral and regional insights
* Identified growth drivers and inefficiencies

---

##  Key Insights

###  1. Strong Growth in Digital Transactions

* Transactions and app usage show consistent growth over time
* Indicates increasing digital adoption across India

---

###  2. Significant State-Level Variation

* Some states dominate in volume (transactions)
* Others dominate in value (Avg Transaction Value)

 **Insight:** High usage ≠ high spending

---

###  3. Average Transaction Value (AvgTV)

* Certain states show high AvgTV despite lower volume
* Indicates premium user segments

---

###  4. Transaction Type Concentration

* Majority of transactions concentrated in few categories (P2P, recharge, merchant payments)

 **Insight:** Limited diversification in usage behavior

---

###  5. Device Brand Dominance

* Few brands dominate (Xiaomi, Samsung, Vivo)
* Strong regional variation in device usage

---

###  6. Weak Correlation with Population Density

* Population density does not strongly drive transaction volume

 **Insight:** Digital adoption depends more on infrastructure and literacy

---

###  7. Data Discrepancies Found

* Differences observed between district-level and state-level aggregates

 Indicates:

* Missing records
* Aggregation inconsistencies
* Potential data quality issues

---

##  Actionable Recommendations

### 1. Target High-Value States

* Focus premium services where AvgTV is high
* Promote financial products (loans, investments)

---

### 2. Improve Low-Adoption States

* Run awareness campaigns
* Offer incentives (cashbacks, onboarding rewards)

---

### 3. Diversify Transaction Usage

* Encourage merchant payments and financial services
* Reduce dependency on P2P transactions

---

### 4. Device Optimization Strategy

* Optimize app performance for dominant device brands
* Run device-specific campaigns

---

### 5. Fix Data Quality Issues

* Align aggregation across datasets
* Implement validation pipelines
* Handle missing and duplicate records

---

### 6. Time-Based Strategy

* Identify peak transaction quarters
* Launch campaigns before high-growth periods

---

##  Tools & Technologies

* Python (Pandas, NumPy)
* Seaborn & Matplotlib
* Jupyter Notebook

---

##  Conclusion

This analysis highlights that digital payment growth in India is driven by behavioral, regional, and technological factors rather than just population size.

Understanding these patterns enables better targeting, improved product strategy, and scalable growth in digital payment ecosystems.
