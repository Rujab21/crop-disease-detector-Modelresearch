# 🌱 Crop Disease Detector - Model Research

This repository contains the research, experiments, and documentation for the **Crop Disease Detector** project.  
It includes model comparisons, training experiments, and performance evaluation that led to the deployed application.

---

## Contents
- **Jupyter Notebooks** – Training and evaluation experiments  
- **Model Comparison** – Accuracy, loss curves, confusion matrices  
- **Documentation** – Detailed report comparing:
  - MobileNetV2  
  - EfficientNetB3  
  - ConvNeXt-Tiny
     
## Model Research  

We compared three models: **MobileNetV2**, **EfficientNetB3**, and **ConvNeXt-Tiny**.  

### Key Findings  
- **Cotton & Rice** → EfficientNetB3 performed best, with higher accuracy and less overfitting.  
- **Sugarcane** → MobileNetV2 outperformed EfficientNetB3 due to heavy dataset imbalance.  
- **General Case** → EfficientNetB3 is usually better for balanced datasets, while MobileNetV2 handles imbalance better in the short term.  
- **ConvNeXt-Tiny** → Showed strong performance on imbalanced datasets (like sugarcane), with less overfitting and higher robustness.  


---

## Future Work
- Expand dataset with more crop types  
- Experiment with data augmentation techniques  
- Hyperparameter tuning for further accuracy improvements  

---

## Author
- **Rujab Hussain**  
Email: your-email@example.com  
GitHub: [Rujab21](https://github.com/Rujab21)
