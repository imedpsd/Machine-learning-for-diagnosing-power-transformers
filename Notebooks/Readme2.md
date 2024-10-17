# Power Transformer Diagnosis - CSV Creation and Final Model

This folder contains notebooks used for generating `.csv` files and building the final decision tree model for diagnosing power transformer conditions based on Dissolved Gas Analysis (DGA).

## Notebooks

- **[9vectors.ipynb](Machine-learning-for-diagnosing-power-transformers/Notebooks9vectors.ipynb)**: This notebook was used to create the `.csv` files used throughout the project. After several trials (see **Section 4.6.2** in the attached [PFE_BOUKHARI.pdf](PFE_BOUKHARI.pdf)**), we narrowed down the input vectors and preprocessing techniques, resulting in reduced loops and simplified code.
  

- **[Vanilla_ML.ipynb](Machine-learning-for-diagnosing-power-transformers/Notebooks/Vanila_ML.ipynb)** This notebook applies various machine learning methods directly to the vectors using different preprocessing techniques, offering a baseline for comparison.


- **[FinalDecisionTree.ipynb](Machine-learning-for-diagnosing-power-transformers/NotebooksFinalDecisionTree.ipynb)**: This notebook demonstrates the creation of the custom decision tree that achieved the highest diagnostic accuracy. For details on how the final decision tree was built, refer to **Section 4.6** in the attached [PFE_BOUKHARI.pdf](PFE_BOUKHARI.pdf)**.

Both notebooks reflect the refined methods and processes outlined in the full report in **[PFE_BOUKHARI.pdf](PFE_BOUKHARI.pdf)**.
