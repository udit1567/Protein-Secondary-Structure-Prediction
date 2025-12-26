# Protein-Secondary-Structure-Prediction

Predicting the secondary structure of proteins is a central problem in computational biology. The way a protein folds—forming helices, sheets, and loops—determines its function, stability, and interactions. In this Kaggle competition, the goal is to automatically infer the secondary structure of peptide sequences, making it a sequence-to-sequence prediction task where input and output sequences share the same length.

This challenge uses a curated dataset of peptide sequences paired with their experimentally determined secondary structures in two annotation schemes:

Q8 (sst8) — Eight-state secondary structure labels
Q3 (sst3) — A simplified three-state version commonly used in structure prediction
The competition encourages participants to build models that map an amino-acid sequence (e.g., "ACDEFGHIK") to its corresponding structural sequence.

It is also encouraged to use bidirectional sequence-to-sequence model.
