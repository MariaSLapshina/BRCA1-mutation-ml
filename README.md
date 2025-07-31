**Predicting the impact of BRCA1 missense mutations using machine learning**

Background: BRCA1 is a critical tumor suppressor; missense mutations can disrupt its function and increase cancer risk. Computational prediction of variant impact can help prioritize mutations for experimental validation and support clinical interpretation

This project uses machine learning to classify BRCA1 variants as benign or pathogenic based on:
* Biochemical property changes (e.g., charge, hydrophobicity)
* Mutation context (position, wild-type vs mutant residue)
* (Planned) Structural features from AlphaFold / PDB models
* (Planned) Evolutionary conservation scores

**Key Results (Current)**
- Logistic Regression:
  * Accuracy ~77%
  * ROC-AUC ~0.78

- Random Forest:
  * Accuracy ~85%
  * ROC-AUC ~0.92
