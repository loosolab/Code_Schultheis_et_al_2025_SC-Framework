# Overview

Single-nucleusATAC human 10k healthy peripheral blood mononuclear cells (PBMCs) of 10x Genomics are analyzed using the ATAC notebooks. First, core analysis steps of assembly, QC, normalization, batch correction, embedding and clustering are done. Then genes are identified and classified as markers followed by cell type annotation and [TOBIAS](https://github.com/loosolab/TOBIAS) analysis.

The `analysis/` directory contains all notebooks in executed state to retrace the analysis. The `report.pptx` in each of the directories provides an overview including descriptions as a presentation. The notebooks may be run to fully re-create the analysis and all related files. Start with the `00-download.ipynb` notebook, which provides links and code to the data used within the analysis. See instructions in `analysis/` for further information.
