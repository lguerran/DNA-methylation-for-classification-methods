# DNA-methylation-for-classification-methods
Many patients suffering from neurodevelopmental disorders remain without a definitive diagnosis. This situation makes it difficult to apply treatments that help manage the disease.

Epigenetics studies changes in gene expression without alterations in the DNA sequence. Many of these diseases are related to epigenetic mechanisms, which will be reflected in the overall DNA methylation landscape.

A total of 1732 methylome samples from patients with neurodevelopmental disorders and healthy controls, covering 13 different classes, have been gathered from 15 public databases. Firstly, the processing and selection of the 1000 probes that best differentiate between classes was performed. With this information, classification models were evaluated using the Support Vector Machine (SVM) and k-Nearest Neighbor (kNN) algorithms.

This methodology could be implemented in clinical practice to resolve the diagnosis of these patients.

The data available in this repository is:
- General script:
  - Loading data
  - Quality control
  - Normalisation
  - Data exploration
  - Filtering
  - Probe-wise differential methylation
  - Support Vector Machine Model
  - k-Nearest Neighbor Model
  
- Subgroup data:
  - Remove low quality data
  - Remove control datasets
  - "> 10 cases per class"
  - "> 30 cases per class"

Script based on the analysis available at: https://www.bioconductor.org/packages/release/workflows/vignettes/methylationArrayAnalysis/inst/doc/methylationArrayAnalysis.html
