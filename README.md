# Support Vector Machines (SVMs) & Kernel Tricks

## Project Overview
This project explores **Support Vector Machines (SVMs)** using different **kernels**, studying their impact on classification accuracy, decision boundaries, and model generalization. Experiments include **linear vs. non-linear separability, kernel transformations, slack parameter tuning, and hybrid kernel combinations**.

## 🛠️ Technologies & Tools Used
- **Programming Language**: Python
- **Libraries**: NumPy, Matplotlib, Scikit-learn
- **Algorithms**: SVM with Linear, Polynomial, and RBF Kernels
- **Evaluation Metrics**: Decision Boundary Analysis, Classification Accuracy, Overfitting Prevention

## 🔍 Key Features
### **📊 Kernel Comparison & Non-Linear Transformations**
- **Tested Linear SVMs** on datasets with varying cluster spreads.
- **Implemented 3D feature mapping** to visualize non-linear separability.
- **Explored RBF Kernel performance with adversarial noise**.

### **📈 Multi-Class Classification & Hybrid Kernels**
- **Implemented One-vs-One SVM** for multi-class problems.
- **Combined linear, polynomial, and RBF kernels** for enhanced adaptability.
- **Tested Manhattan vs. Euclidean distance in RBF kernels**.

### **⚙️ Tuning Hyperparameters**
- **Adjusted slack parameter (C)** to balance margin maximization and misclassification tolerance.
- **Analyzed overfitting risks** due to excessive flexibility in RBF kernel.

## 📊 Results
✔️ **Linear SVMs fail on overlapping data**, requiring **non-linear kernels**.  
✔️ **Polynomial kernels capture curved boundaries**, but high-degree models overfit.  
✔️ **RBF kernel achieves best separation**, but is **sensitive to noise**.  
✔️ **Hybrid kernels balance flexibility and generalization**, requiring careful tuning.  

## 🔄 Future Improvements
- Test **auto-tuned kernel selection** for optimal generalization.
- Implement **semi-supervised SVMs** for partially labeled datasets.
- Compare **SVM vs. Neural Networks** for large-scale classification.

---
