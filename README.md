# SHBT261_MiniProject1_CeceJen
Mini-Project 1: Image Classification with Caltech-101 Dataset

### Your Goals
- Train and evaluate at least three different methods for image classification. For example: ResNet, EfficientNet, ViT, and newer ones.
- Compare classical machine learning and deep learning methods.
- Write a report including:
  – Methods
  – Results (metrics + plots)
  – Observations, and/or Ablation stidues
  – Interpretations and Lessons learned
- Deliver Report, Notebooks, and/or Scripts, figures.

### Dataset Preparation
- Download [Caltech-101 Dataset](https://www.kaggle.com/datasets/imbikramsaha/caltech-101)
- Split: Use 70% train, 15% validation, 15% test (stratified)

### Evaluation Metrics
Each model must be evaluated using:
- Accuracy (overall performance).
- Per-class accuracy (to see class imbalance effects).
- Confusion matrix (visualize misclassification).
- Precision, Recall, F1-Score (macro & weighted averages).
- Top-k accuracy (optional, e.g., Top-5).

### Ablation Studies
To deepen learning, run at least two small ablation experiments:
- Image size: compare 64 × 64 vs. 128 × 128
- Data augmentation: train with vs without augmentation.
- Feature extractor choice: HOG vs CNN features.
- Optimizer: SGD vs Adam for CNN
