skills:

name: load_dataset
description: Reads the ward_budget.csv dataset, validates columns and reports null rows.
input: CSV file path
output: Dataset with null row report
error_handling: Stop execution if file or columns are missing.

name: compute_growth
description: Computes Month-over-Month growth for a specific ward and category.
input: Dataset, ward name, category name, growth_type
output: Per-period growth table
error_handling: Stop execution if growth_type is missing or data invalid.
