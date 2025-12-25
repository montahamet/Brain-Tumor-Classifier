## Brain Tumor MRI Classification using CNN(EfficientNetB1)

This repository contains a comprehensive **Deep Learning pipeline** for the automated **detection and classification of brain tumors from MRI scans**.  
Utilizing **transfer learning with the EfficientNetB1 architecture**, the model classifies images into four distinct categories:

- **Glioma**
- **Meningioma**
- **Pituitary Tumor**
- **No Tumor**

---

## Key Features

### Automated Image Preprocessing
Includes a custom **computer vision pipeline using OpenCV** to automatically crop the brain from MRI scans by detecting extreme contours, effectively removing non-informative background noise.

### Robust Data Augmentation
Implements real-time augmentation techniques such as **rotation, shifting, and flipping** to improve model generalization and combat overfitting.

### Transfer Learning
Leverages the **EfficientNetB1 backbone**, pre-trained on **ImageNet**, for high-performance feature extraction in medical imaging.

### Advanced Evaluation
Includes detailed diagnostic metrics such as **learning curves, confusion matrices, and precision/recall classification reports**.

---

## Model Architecture

### EfficientNetB1 Architecture

EfficientNetB1 uses compound scaling to balance **network depth, width, and resolution**, making it efficient and well-suited for medical image classification tasks.

**EfficientNetB1 Architecture Diagram**

<img width="850" height="233" alt="Architecture-of-EfficientNetB1" src="https://github.com/user-attachments/assets/46948fba-3497-495b-8a99-f6e6b00f8f3a" />


```markdown
![EfficientNetB1 Architecture](assets/efficientnetb1.png)
