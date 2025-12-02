Follow the order below to reproduce the scRNA analysis. All files but the executed notebooks are excluded from this repository to save space. Run the notebooks to re-create all analysis files.

## Download data

First, run the `00-download.ipynb` notebook to load all required data files and store them at the expected location.

## Analysis

Individual analysis was conducted per timepoint.

### 1.5 dpf analysis order:
- 01_assembling_anndata.ipynb
- 02_QC_filtering.ipynb
- 03_normalization_batch_correction.ipynb
- 04_clustering.ipynb
- group_markers.ipynb
- annotation.ipynb
- 99-report.ipynb

### 2 dpf analysis order:
- 01_assembling_anndata.ipynb
- 02_QC_filtering.ipynb
- 03_normalization_batch_correction.ipynb
- 04_clustering.ipynb
- group_markers.ipynb
- annotation.ipynb
- 99-report.ipynb

### 3 dpf analysis order:
- 01_assembling_anndata.ipynb
- 02_QC_filtering.ipynb
- 03_normalization_batch_correction.ipynb
- 04_clustering.ipynb
- group_markers.ipynb
- annotation.ipynb
- 99-report.ipynb

### 5 dpf analysis order:
- 01_assembling_anndata.ipynb
- 02_QC_filtering.ipynb
- 03_normalization_batch_correction.ipynb
- 04_clustering.ipynb
- group_markers.ipynb
- annotation.ipynb
- 99-report.ipynb

### 14 dpf analysis order:
- 01_assembling_anndata.ipynb
- 02_QC_filtering.ipynb
- 03_normalization_batch_correction.ipynb
- 04_clustering.ipynb
- group_markers.ipynb
- annotation.ipynb
- 99-report.ipynb

### 60 dpf analysis order:
- 01_assembling_anndata.ipynb
- 02_QC_filtering.ipynb
- 03_normalization_batch_correction.ipynb
- 04_clustering.ipynb
- group_markers.ipynb
- annotation.ipynb
- 99-report.ipynb

### 150 dpf analysis order:
- 01_assembling_anndata.ipynb
- 02_QC_filteirng.ipynb
- 03_normalization_batch_correction.ipynb
- 04_clustering.ipynb
- group_markers.ipynb
- annotation.ipynb
- group_markers_post_annotation.ipynb
- GSEA.ipynb
- 99-report.ipynb

### all dpf analysis order:

After analysis of individual timepoints, everything is combined and a global analysis is done.

- 01_assembling_anndata.ipynb
- 03_normalization_batch_correction.ipynb
- 04_clustering.ipynb
- group_markers.ipynb
- annotation.ipynb
- group_markers_post_annotation.ipynb
- proportion_analysis.ipynb
- 0A1_ligand_receptor.ipynb
- 0A2_ligand_receptor_hub_genes.ipynb
- 99-report.ipynb
