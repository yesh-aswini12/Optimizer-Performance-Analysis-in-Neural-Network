# 📌 Comparison of Optimization Methods for Classification

This project compares different **optimization algorithms** for training a Multi-Layer Feedforward Neural Network (**MLFFNN**) on an image classification dataset.  

---

## 🧠 Model Architecture
- **Type:** Multi-Layer Feedforward Neural Network (MLFFNN)  
- **Hidden Layers:**  
  - Layer 1: 20 nodes  
  - Layer 2: 10 nodes  
- **Activation Function:** Tanh  
- **Loss Function:** Cross-Entropy  
- **Learning Mode:** Pattern mode  
- **Stopping Criterion:** Training stops when the change in average error falls below a threshold  

---

## ⚡ Optimization Methods Compared
1. **Delta Rule**  
2. **Generalized Delta Rule**  
3. **AdaGrad**  
4. **RMSProp**  
5. **Adam**  

🔹 All optimizers were tested with:  
- Same initial random weights  
- Same learning rate  

---

## 📊 Results
For each optimization rule, the following analyses were carried out:  
- 📈 **Average Error vs Epoch** (convergence plot)  
- 🔢 **Confusion Matrices** for both training and test data  
- ⏳ **Number of Epochs** required for convergence  

All results (plots, confusion matrices) are available in the `results/` folder.  

---
