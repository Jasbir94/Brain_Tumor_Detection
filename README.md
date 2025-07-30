Project Summary
The project develops a hybrid AI model (ViT-CB) to enhance brain tumor detection and classification using MRI images. Key innovations include:

Integration of Vision Transformer (ViT) for automated feature extraction from brain MRI scans.

Dimensionality reduction using Principal Component Analysis (PCA) to refine features.

Classification via the CatBoost algorithm (optimized with Optuna) for improved accuracy.

Model interpretability using SHAP-based Explainable AI (XAI) to identify critical features influencing predictions.
The model achieved 99.32% accuracy on a binary dataset (tumor/no tumor) and 99.00% accuracy on a multi-class dataset (glioma, meningioma, pituitary, no tumor), outperforming existing state-of-the-art methods.
