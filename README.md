# Deep-DNABERT
Hybrid feature and transformer-based deep learning framework for cross-species DNA 6mA site prediction using DNABERT embeddings and handcrafted biological descriptors.
# Topics
bioinformatics
DNA
6mA
DNABERT
deep-learning
machine-learning
transformer
SHAP
sequence-analysis
epigenetics
jupyter-notebook
python

# Deep-DNABERT Repository Structure

```text
Deep-DNABERT/
│
├── README.md
├── LICENSE
├── requirements.txt
├── environment.yml
├── setup.py
├── CITATION.cff
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
│
├── datasets/
│   ├── benchmark/
│   │   ├── Benchmarking Positive Dataset.txt
│   │   └── Benchmarking Negative Dataset.txt
│   │
│   ├── independent/
│   │   ├── Independent Positive Dataset.txt
│   │   └── Independent Negative Dataset.txt
│   │
│   └── csv_features/
│       ├── TACC/
│       ├── PseNAC/
│       ├── PseDNC/
│       ├── SCPseTNC/
│       ├── DNABERT/
│       └── Hybrid/
│
├── notebooks/
│   ├── NB_Classifier.ipynb
│   ├── KNN_Classifier.ipynb
│   ├── DT_Classifier.ipynb
│   ├── SVM_Classifier.ipynb
│   ├── RF_Classifier.ipynb
│   ├── XGBoost_Classifier.ipynb
│   ├── AdaBoost_Classifier.ipynb
│   ├── Deep_DNABERT_Classifier.ipynb
│   ├── Deep_DNABERT_Full_DNN_Notebook.ipynb
│   └── Deep_DNABERT_All_Classifiers.ipynb
│
├── src/
│   ├── preprocessing/
│   ├── feature_extraction/
│   ├── feature_selection/
│   ├── classifiers/
│   ├── evaluation/
│   ├── visualization/
│   └── utils/
│
├── models/
│   ├── trained_models/
│   │   ├── nb_model.pkl
│   │   ├── knn_model.pkl
│   │   ├── dt_model.pkl
│   │   ├── svm_model.pkl
│   │   ├── rf_model.pkl
│   │   ├── xgboost_model.pkl
│   │   ├── adaboost_model.pkl
│   │   └── deep_dnabert_model.h5
│   │
│   └── checkpoints/
│       ├── best_model_checkpoint.h5
│       └── training_logs.txt
│
├── outputs/
│   ├── figures/
│   ├── tables/
│   ├── logs/
│   └── predictions/
│
├── manuscript/
│   ├── manuscript.docx
│   ├── manuscript.pdf
│   ├── supplementary_material.pdf
│   └── response_to_reviewers.docx
│
└── docs/
    ├── installation.md
    ├── methodology.md
    ├── reproducibility.md
    ├── usage.md
    └── dataset_description.md
```
