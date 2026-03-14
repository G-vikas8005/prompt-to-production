skills:

name: load_dataset
description: Reads the ward_budget.csv dataset, validates required columns, and reports rows where actual_spend is null.
input: CSV file path containing budget dataset.
output: Dataset loaded into memory and printed report of null rows.
error_handling: If the file or columns are missing, stop execution with an error.

name: compute_growth
description: Computes Month-over-Month growth for a selected ward and category.
input: Dataset, ward name, category name, growth_type.
output: Per-period table showing growth percentage and formula used.
error_handling: If growth_type is missing or invalid, refuse execution.
