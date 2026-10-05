# ml-assignment-2-pandas

## Dataset
Texas housing sales (`txhousing`), 8,602 rows. Source: https://ggplot2.tidyverse.org/reference/txhousing.html

The submitted `txhousing_assignment2.csv` is the public `txhousing` data with one deterministic helper field, `sale_date = first day of year/month`, added so the assignment's `parse_dates` requirement can be demonstrated directly.

## Required reported numbers
- Memory before optimization: 1,877,812 bytes
- Memory after optimization: 341,705 bytes
- Memory saving: **81.80%**
- Cleaned CSV size observed in this run: **891,921 bytes**
- Parquet size: **183,789 bytes**

## Files to submit
- `assignment2_pandas.ipynb`
- `txhousing_assignment2.csv`
- `README.md`

Before submitting, use **Runtime → Restart and run all** in Colab. Question 13 installs `pyarrow` there if needed, writes the Parquet file, prints the exact size/load-time comparison, and updates the Parquet-size line above automatically.
