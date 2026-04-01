# Deep Learning Assignment - CIFAR-10 Classification

## 📌 Overview
This project implements multiple deep learning models for image classification on the CIFAR-10 dataset.  
The goal is to compare different model architectures, from simple baseline models to advanced approaches.

---

## 📊 Models Implemented

### Baseline
- Softmax Regression  
- MLP  

### CNN
- Convolutional Neural Network  

### Transformer
- Vision Transformer (ViT)
  - Built-in TransformerEncoder  
  - Custom TransformerEncoder  

### Hybrid
- CNN+Transformer (64 tokens)  
- CNN+Transformer (16 tokens)  

### Sequence Models
- GRU (row-wise)  
- GRU (patch-wise)  

---

## 📁 Project Structure

```
01-softmax-and-mlp/
02-cnn/
03-vit/
04-hybrid-architecture-and-gru/
report/
README.md
```

---

## ⚙️ Requirements

- Python 3.9+
- PyTorch
- torchvision
- matplotlib
- numpy

Install:
```
pip install torch torchvision matplotlib numpy
```

---

## ▶️ How to Run

### Google Colab (recommended)
1. Upload notebook  
2. Enable GPU  
3. Run all cells  

### Local
```
jupyter notebook
```

---

## 📊 Dataset
- CIFAR-10 (auto-downloaded via torchvision)

---

## 📈 Metrics
- Train Accuracy  
- Test Accuracy  
- Train Loss  
- Test Loss  
- Training Time  

---

## 📌 Notes
- All models use the same dataset and settings for fair comparison  
- Results are shown in notebooks and report  
- Hybrid models combine CNN + Transformer  
- GRU models explore sequence representations  

---

## 👥 Authors
- Khoa  
- Hieu  
- Thanh  
- Tri  

---

## 📎 Submission
- Report (PDF)  
- Source code (notebooks)  
- README  
