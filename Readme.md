# RELICS SMACS0723 HST Analysis

Photometric analysis of SMACS J0723.3-7327 galaxy cluster using HST WFC3/IR data (F105W, F160W).
Summer 2022 Simple Research Internship project. (Revised in 2023 and 2025 for organization.)

## Data Source
- RELICS (Reionization Lensing Cluster Survey): https://archive.stsci.edu/prepds/relics/

## Structure
```
CODE/
├── 01_run_SExtractor.ipynb    # SExtractor configuration & execution
├── 02_main_plot.ipynb         # Basic photometry plots & catalog matching
├── 03_outlier_analysis.ipynb  # Outlier identification
└── 04_source_type_analysis.ipynb  # Point/Extended source classification

DATA/       # Reference catalogs
RESULT/     # SExtractor output (.cat files)
```

## Analysis Flow
1. Run SExtractor on reduced images
2. Match SExtractor output with reference catalog
3. Analyze outliers and source types (point vs extended)

## Requirements
- Python 3.7+
- numpy, matplotlib, astropy, pandas
- SExtractor
