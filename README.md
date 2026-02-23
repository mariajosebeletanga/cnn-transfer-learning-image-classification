# cnn_transfer_learning_image_classification

Deep learning project comparing a custom convolutional neural network (CNN) trained from scratch with a pretrained ResNet model using transfer learning for image classification.


# CNN vs ResNet Transfer Learning for Image Classification

## 📌 Project Overview

This project explores the effectiveness of transfer learning compared to training deep neural networks from scratch on image classification tasks.

A baseline CNN model was developed and trained end-to-end, and its performance was compared against a pretrained ResNet architecture fine-tuned on the same dataset. The goal was to evaluate accuracy, training efficiency, and generalization performance.

---

## 📊 Dataset

- CIFAR-10 image dataset  
- 60,000 color images across 10 classes  
- Standard train/test split  

---

## 🧠 Methodology

### Custom CNN Model
- Convolutional layers with ReLU activations  
- Pooling layers for spatial reduction  
- Fully connected classification head  
- Trained from scratch  

### Transfer Learning Model
- Pretrained ResNet architecture  
- Frozen backbone layers  
- Fine-tuned classification head  
- Faster convergence and improved performance  

---

## 📈 Key Results

- CNN trained from scratch achieved strong baseline performance  
- ResNet transfer learning reached higher accuracy with fewer training epochs  
- Transfer learning reduced overfitting and improved training efficiency  

---

## 🎯 Key Takeaways

- Pretrained deep networks significantly improve performance on limited datasets  
- Transfer learning reduces training time while increasing generalization  
- CNN architecture design remains critical for baseline modeling  

---

## 📂 Repository Contents

- `notebooks/` – Deep learning training and evaluation pipeline  
- `report/` – Detailed experimental analysis and results  

---

## 🛠 Tools & Technologies

- Python  
- PyTorch / TensorFlow (depending on your implementation)  
- CNN architectures  
- Transfer learning with ResNet  
- Model evaluation metrics  
