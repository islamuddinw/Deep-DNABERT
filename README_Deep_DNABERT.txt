
# Deep-DNABERT

Deep-DNABERT is a hybrid feature and transformer-based framework developed for cross-species DNA N6-methyladenine (6mA) site prediction.

===========================================================
OVERVIEW
===========================================================

This repository contains the official implementation of:

Deep-DNABERT: A Hybrid Feature and Transformer-Based Framework for Cross-Species DNA 6mA Site Prediction

The proposed framework integrates:

- Handcrafted DNA descriptors
- DNABERT contextual embeddings
- Hybrid feature fusion
- SHAP-based explainability
- Deep neural network classification

for robust and interpretable DNA 6mA site prediction.

===========================================================
FEATURE REPRESENTATIONS
===========================================================

| Feature Type | Description | Dimension |
|--------------|-------------|------------|
| TACC | Trinucleotide Auto-Cross Covariance | 12 |
| PseNAC | Pseudo Nucleic Acid Composition | 20 |
| PseDNC | Pseudo Dinucleotide Composition | 30 |
| SCPseTNC | Series Correlation Pseudo Trinucleotide Composition | 64 |
| DNABERT | Contextual k-mer DNA embeddings | 768 |
| Hybrid | Concatenation of all features | 894 |

===========================================================
DATASETS
===========================================================

Benchmark Dataset
-----------------
- Positive samples: 2500
- Negative samples: 2500

Independent Dataset
-------------------
- Positive samples: 268
- Negative samples: 216

All DNA fragments were standardized to 41 bp sequence length.

===========================================================
IMPLEMENTED CLASSIFIERS
===========================================================

- Naive Bayes (NB)
- K-Nearest Neighbor (KNN)
- Decision Tree (DT)
- Support Vector Machine (SVM)
- Random Forest (RF)
- XGBoost
- AdaBoost
- Deep-DNABERT (Proposed)

===========================================================
REPOSITORY STRUCTURE
===========================================================

Deep-DNABERT/
|
|-- datasets/
|-- notebooks/
|-- src/
|-- models/
|-- outputs/
|-- manuscript/
|-- docs/

===========================================================
INSTALLATION
===========================================================

Clone repository:

git clone https://github.com/yourusername/Deep-DNABERT.git

Install dependencies:

pip install -r requirements.txt

===========================================================
NOTEBOOKS
===========================================================

Included notebooks:

- NB_Classifier.ipynb
- KNN_Classifier.ipynb
- DT_Classifier.ipynb
- SVM_Classifier.ipynb
- RF_Classifier.ipynb
- XGBoost_Classifier.ipynb
- AdaBoost_Classifier.ipynb
- Deep_DNABERT_Classifier.ipynb
- Deep_DNABERT_Full_DNN_Notebook.ipynb
- Deep_DNABERT_All_Classifiers.ipynb

===========================================================
DATA AVAILABILITY
===========================================================

The datasets analyzed during the current study, processed feature representations, source code, trained models, and Jupyter notebooks are publicly available in the Deep-DNABERT repository.

===========================================================
LICENSE
===========================================================

MIT License

===========================================================
CONTACT
===========================================================

Islam Uddin
Email: islamuddin@awkum.edu.pk
