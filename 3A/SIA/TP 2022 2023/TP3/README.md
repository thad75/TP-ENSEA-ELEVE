# 🧠 Self-Supervised Learning  

In previous classification tasks, we relied on large amounts of labeled data for each class, enabling models to achieve high accuracy given enough samples. However, in real-world scenarios, **large labeled datasets are often unavailable**, while vast amounts of **unlabeled data** exist.  

This lab explores **self-supervised learning**, a strategy that allows us to extract useful features from unlabeled data (Representation Learning) before fine-tuning a classifier on a smaller labeled dataset. One successful approach is **pretext tasks**, which involve training a model on an **auxiliary task** before transferring part of the network as a feature encoder for downstream tasks.  

---

## 🎯 Learning Objectives  

By the end of this lab, you will:  
- **Understand representation learning** through pretext tasks.  
- **Practice fine-tuning** pre-trained models with limited labeled data.  
- **Explore industrial applications** of self-supervised learning.  
- **Use PyTorch Lightning** to streamline training.  

---

## 🏭 Industrial Applications  

### **1️⃣ Classifying Street Numbers with Few Labeled Data**  
Imagine building a model to recognize **street numbers** from street view imagery. You have access to a vast number of images but only a **tiny fraction is labeled**. This section explores how **pretext tasks** can help leverage the unlabeled set for improved classification performance.  

### **2️⃣ Face Anomaly Detection**  
This section applies self-supervised learning to **anomaly detection**. The approach is based on the idea that a model trained on a pretext task (e.g., detecting 90° rotations) will struggle on data that significantly differs from the training distribution. Using the **CelebA dataset**, we train a model to recognize rotated faces, then evaluate its performance on **outlier detection**.  

---

## 🚀 Why This Lab?  

- **Bridges the gap between supervised and unsupervised learning**.  
- **Solves real-world problems where labeled data is scarce**.  
- **Introduces transferable skills in self-supervised learning and fine-tuning**.  

Get ready to explore self-supervised learning and unlock the potential of unlabeled data! 🚀  