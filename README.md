# Interactive 3D PCA: *Fraxinus* Population Structure

This repository hosts an interactive 3D Principal Component Analysis (PCA) visualization of filtered genomic data for North American ash trees (*Fraxinus* spp.), incorporating latitudinal gradients.

## 📊 Interactive Visualization
**[Click here to view the Interactive 3D PCA Plot](https://github.com/Eaglet77/haolin/blob/main/Total_Filtered_indv95_miss60_DP54_mac3_ld05_PCA_3D_lat.html)**

*(Note: Replace the URL above with your actual GitHub Pages link once activated).*

## 🧬 Dataset & Filtering Parameters

The interactive plot (`Total_Filtered_indv95_miss60_DP54_mac3_ld05_PCA_3D_lat.html`) was generated from variant call data subjected to rigorous quality control. The filename reflects the following filtering pipeline:

* **Total_Filtered**: Final working dataset after initial QC.
* **indv95**: Individuals with high missing data were removed (e.g., retaining those with $\ge$ 95% call rate).
* **miss60**: Loci missing data threshold filtering.
* **DP54**: Depth of coverage filtering parameters applied.
* **mac3**: Minor Allele Count (MAC) threshold set to 3 to remove rare variants.
* **ld05**: Linkage Disequilibrium (LD) pruning applied with an $r^2$ threshold of 0.5 to ensure independent markers.
* **PCA_3D_lat**: 3D PCA projection, with sample distribution visualized across latitudinal (`lat`) gradients.

## 🛠️ Usage
Since this is an interactive HTML file generated via R (e.g., `plotly`), you can rotate, zoom, and hover over individual data points to inspect specific samples (e.g., differentiating *F. pennsylvanica*, *F. americana*, and their hybrids). 

Download the `.html` file and open it in any modern web browser (Chrome, Safari, Firefox) for local viewing, or use the GitHub Pages link above for web access.
