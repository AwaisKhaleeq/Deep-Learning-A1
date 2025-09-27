# Assignment 1 – Short Report

## 📊 Dataset
- **Number of samples:** 3999  
- **Train samples:** 3199  
- **Validation samples:** 800  

## 🏗️ Models & Training
- **Baselines:**  
  - ResNet50 (transfer learning)  
  - EfficientNetB0 (transfer learning)  

---

## 🔹 ResNet50 Results
- **Accuracy:** 1.0  
- **F1-macro:** 1.0  
- **Cohen’s Kappa:** NaN  
- **Krippendorff’s Alpha:** 1.0  
- **AUC-OVR:** NaN  
- **PR AUC-macro:** 0.5  

**Regression Metrics**  
- Valence RMSE: `0.4368`  
- Arousal RMSE: `0.5889`  
- Valence Corr.: NaN  
- Arousal Corr.: NaN  
- Valence SAGR: 0.0  
- Arousal SAGR: 0.0  
- Valence CCC: 0.0  
- Arousal CCC: 0.0  

---

## 🔹 EfficientNetB0 Results
- **Accuracy:** 1.0  
- **F1-macro:** 1.0  
- **Cohen’s Kappa:** NaN  
- **Krippendorff’s Alpha:** 1.0  
- **AUC-OVR:** NaN  
- **PR AUC-macro:** 0.5  

**Regression Metrics**  
- Valence RMSE: `1.93e-06`  
- Arousal RMSE: `2.13e-05`  
- Valence Corr.: NaN  
- Arousal Corr.: NaN  
- Valence SAGR: 0.0  
- Arousal SAGR: 0.0  
- Valence CCC: 0.0  
- Arousal CCC: 0.0  

---

## 📌 Notes
- Both models achieved **perfect classification performance** on the validation set.  
- Regression results were weak or degenerate (NaN correlations, zero SAGR/CCC).  
- Possible causes: dataset simplicity, label imbalance, or task dominance by classification.  
- Future improvements: fine-tuning backbones, adjusting loss weights, and verifying train/val split.  
