Follow the order below to reproduce the snATAC analysis. All files but the executed notebooks are excluded from this repository to save space. Run the notebooks to re-create all analysis files.

## Download data

First, run the `00-download.ipynb` notebook to load all required data files and store them at the expected location.

## Analysis

### 01-analysis-run order:
- 01_assembling_anndata.ipynb
- 02_QC_filtering.ipynb
- 03_normalization_batch_correction.ipynb
- 04_clustering.ipynb
- group_markers.ipynb
- annotation.ipynb
- 0A_tobias.ipynb
- 99-report.ipynb
