# vector_machines
Support Vector Machine (SVM) Classification
🎯 Objective
Implement Support Vector Machines for linear and non-linear binary classification using the Breast Cancer dataset.
📋 Task Requirements Completed
✅ Load and prepare dataset for binary classification
✅ Train SVM with linear and RBF kernels
✅ Visualize decision boundary using 2D data
✅ Tune hyperparameters (C and gamma)
✅ Use cross-validation for performance evaluation

🛠️ Tools Used
Libraries: Scikit-learn, NumPy, Matplotlib, Seaborn
Dataset: Breast Cancer Dataset (569 samples, 30 features)
Techniques: Grid Search, Cross-validation, Feature Scaling

📊 Results Summary
Model Performance:
Linear SVM: 96.49% accuracy (96.03% CV score)
RBF SVM: 92.98% accuracy (94.05% CV score)
Best Tuned SVM: 97.37% accuracy (97.14% CV score)

Best Parameters: C=10, gamma=0.01, kernel=RBF
🚀 How to Run
Install packages: pip install scikit-learn numpy matplotlib seaborn pandas
Run: python svm_classification.py

📁 Files
svm_classification.py - Main implementation
README.md - This file
requirements.txt - Dependencies

🎓 Key Learnings
Margin Maximization: SVM finds optimal decision boundary
Kernel Trick: RBF handles non-linear data better than linear
Hyperparameter Tuning: Improved accuracy by 4.4%
Cross-validation: Ensures robust model evaluation
