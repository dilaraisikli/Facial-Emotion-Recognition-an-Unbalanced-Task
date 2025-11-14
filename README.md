# $$\mathbf{Facial\ Emotion\ Recognition\ -\ An\ Unbalanced\ Task}$$

## $$\mathbf{Overview}$$

This project tackles **facial emotion recognition** on the **FER-2013** dataset, focusing specifically on the challenges introduced by **severe class imbalance** and noisy labels.

We classify **7 basic emotions**:

- Angry  
- Disgust  
- Fear  
- Happy  
- Neutral  
- Sad  
- Surprise  

Main goals:

- Design a **compact CNN** that works well on a relatively small, noisy dataset.  
- Mitigate class imbalance via **batch balancing** and **loss design**.  
- Improve robustness and generalization using **data augmentation**.  
- Interpret model decisions via **Grad-CAM** visualizations.  

---

## $$\mathbf{Dataset}$$

We use the **FER-2013** dataset:

- \(\approx 35{,}887\) grayscale images  
- Resolution: \(48 \times 48\)  
- 7 emotion classes (as listed above)  
- Strong **class imbalance** (some emotions have far fewer samples)  
- Labels are known to be **noisy**, so a perfect accuracy of \(1.0\) is unrealistic  

