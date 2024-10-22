# Single-cell-analysis
The analysed file is an RDS object, a list containing:
- **Count**: A matrix of single cells against genes.
- **Metadata**: Metadata corresponding to the count matrix, including cell type, label, and replicate.

This dataset has 2 conditions (Disease vs Control), 15 cell types, and 5 replicates.

### Task 1
Evaluate biological insights from single-cell data with perturbations:
1. **Identify differentially expressed genes** between the 2 conditions. Provide a final table with:
   - Cell type
   - Gene
   - Effect size (log-2 fold change)
   - P-value
   - Adjusted p-value
2. **Rank cell types** by how much they are perturbed, from most to least.

You may use any methods or propose your own for these analyses. Additional insights are welcome.

### Task 2
From a translational perspective, explore single-cell sequencing for phenotypic classification:
1. **Build a classifier** to predict disease vs control. Consider:
   - Should the classifier be cell-type specific?
   - Train-test split: replicate-based or cell-based?

2. Provide results for your best classifier:
   - Accuracy
   - Area under the ROC
   - Confusion matrix

For both tasks, please include scripts and relevant data visualizations.
