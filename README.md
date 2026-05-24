## Brief Summary

**Dataset:** Indian E-Commerce Products  
**Original:** 1000 rows × 24 columns

### What I Did
- Loaded CSV into Pandas DataFrame
- Explored data — shape, columns, dtypes, head/tail
- Handled missing values — filled discount with 0, seller_name with Unknown
- Cleaned final_price — removed ₹ symbol, converted to float
- Filtered rows with rating >= 4.0
- Selected useful columns for analysis
- Removed duplicates — 0 found
- Created derived column: total_amount = final_price × ratings_count
- Saved cleaned file as Combined_dataset_CLEANED.csv

### Key Stats
| | Value |
|---|---|
| Total Products | 1000 |
| Categories | 97 |
| Avg Final Price | ₹1,706 |
| Duplicates | 0 |
