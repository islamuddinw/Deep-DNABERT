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
# Complete Repository Structure
Deep-DNABERT/
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
│   │   ├── figure1_workflow.png
│   │   ├── figure2_shap_summary.png
│   │   ├── figure3_dependence_plot.png
│   │   ├── figure4_dnn_architecture.png
│   │   ├── figure5_loss_curve.png
│   │   ├── figure6_hyperparameter_analysis.png
│   │   ├── figure7_classifier_comparison.png
│   │   ├── figure8_confusion_matrix.png
│   │   ├── figure9_roc_5fold.png
│   │   ├── figure10_roc_10fold.png
│   │   └── figure11_independent_testing.png
│   │
│   ├── tables/
│   │   ├── table1_dataset_summary.csv
│   │   ├── table2_feature_dimensions.csv
│   │   ├── table3_hyperparameters.csv
│   │   ├── table4_classifier_results.csv
│   │   └── table5_statistical_analysis.csv
│   │
│   ├── logs/
│   │   ├── training_log.txt
│   │   └── evaluation_log.txt
│   │
│   └── predictions/
│       ├── prediction_results.csv
│       └── probability_scores.csv
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
