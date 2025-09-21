# 🫁 Lung Cancer Detection using Deep Learning

<img width="1536" height="1024" alt="lc" src="https://github.com/user-attachments/assets/d0afde76-bcf2-4893-ad26-553105de68e5" />

This project focuses on the application of **deep learning models** for the early detection of **lung cancer** using CT scan images.  
By leveraging **Convolutional Neural Networks (CNNs)** and medical imaging techniques, the project aims to provide an efficient and automated approach to assist radiologists in diagnosing lung cancer.

---

## 📂 Repository Structure
- `Lung Cancer Detection (2).pdf` → Full project report.  
- `lung_cancer_detection.ipynb` → Jupyter Notebook with preprocessing, model training, and evaluation.  

---

## 🧪 Methodology
- **Dataset**: Lung CT scan dataset with labeled cancerous and non-cancerous samples.  
- **Preprocessing**:  
  - Image resizing & normalization.  
  - Data augmentation for robust training.  
- **Model**:  
  - Convolutional Neural Networks (CNNs) with multiple convolutional + pooling layers.  
  - Dense layers for classification (cancer / no cancer).  
- **Tools**: Python, TensorFlow/Keras, OpenCV, NumPy, Matplotlib.  

---

## 📊 Results
| Metric       | Score |
|--------------|-------|
| Accuracy     | ~95%  |
| Precision    | ~93%  |
| Recall (Sensitivity) | ~94%  |
| F1-Score     | ~93%  |

- The model successfully detected lung cancer with high accuracy.  
- Misclassifications were mostly borderline cases with low image clarity.  

---

## 🖼️ Visualizations
- Example CT scan slices (cancer vs non-cancer).  
- Training/validation accuracy and loss curves.  
- Confusion matrix showing classification performance. 
