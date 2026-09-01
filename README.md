# Thailand
In this repository you can find the Matlab code we used for the paper "Four decades of dengue epidemic patterns in Thailand: clusters and the role of border provinces".

The program expects a directory containing one CSV file per each of the 77 provinces of Thailand:

For each CSV:
- There must be a numeric column named exactly Incidence_norm. This column contains the monthly dengue incidence per 100,000 habitants.
- Each row represents one month.
- All files must have the same number of rows.
- Rows must refer to the same dates, in the same chronological order, across all provinces.
- There should be no missing or infinite incidence values.
