# E. coli Protein Localization Analysis

This repository demonstrates how to:

- **Fetch and split data** from the [UCI E. coli dataset](https://archive.ics.uci.edu/dataset/39/ecoli)  
  - Data is divided into training (70%), validation (15%), and test (15%) sets.
- **Preprocess features**  
  - Standardize all features (mean and variance).
  - Convert target labels to binary (cytoplasm = 1, otherwise = 0).
- **Train SVM models** with multiple kernels (linear, polynomial, RBF, sigmoid)  
  - Systematically tune the penalty parameter \(C\).
  - Compare error rate, precision, recall, and \(F_\beta\) for each model.
- **Evaluate results**  
  - Present performance metrics on the validation and test sets.
  - Identify the best \(C\) value and kernel for optimal classification.

The notebook includes code snippets for each step, along with concise commentary. Use it to explore various SVM kernels and hyperparameters on a binary classification task involving protein localization sites.```
