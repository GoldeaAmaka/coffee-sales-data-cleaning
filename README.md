# Coffee Sales Data Cleaning & Feature Engineering

## Project Overview
This project demonstrates an end-to-end data cleaning and preprocessing workflow using **Python and Pandas**.  
The goal was to transform raw coffee sales transaction data into a clean, structured, and analysis-ready dataset suitable for business insights and reporting.

---

## Dataset
- Raw coffee sales transaction data
- Contains timestamps, payment information, product names, and transaction values
- Source: Public dataset (used strictly for learning and portfolio purposes)

---

## Data Cleaning & Preparation Steps
The following steps were performed:

1. **Data Inspection**
   - Checked dataset shape, column names, data types
   - Identified missing values and duplicates

2. **Handling Missing Values**
   - Verified null values across all columns
   - Handled missing payment-related fields appropriately

3. **Data Type Corrections**
   - Converted date and datetime columns to proper datetime formats

4. **Feature Engineering**
   - Extracted `hour_of_day` from datetime
   - Derived `day_of_week`
   - Created `is_weekend` flag for weekday vs weekend analysis

5. **Standardisation**
   - Cleaned and standardised coffee product names
   - Ensured consistent naming conventions

6. **Column Renaming**
   - Renamed fields for clarity (e.g., `cash_type` → `payment_method`)

---

## Final Clean Dataset Includes
- Date & timestamp
- Hour of transaction
- Day of week
- Weekend indicator
- Coffee product name
- Payment method
- Transaction amount

The final dataset is clean, readable, and ready for exploratory analysis or dashboarding.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- Google Colab
- GitHub

---


