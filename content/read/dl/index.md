---
title: "Deep Learning Student Roadmap"
summary: "A structured roadmap for UG students to master Neural Networks, CNNs, RNNs, and Transformers using PyTorch."
date: 2026-02-24
type: page
---

# 🚀 Deep Learning Student Roadmap

This roadmap is designed for undergraduate students transitioning from Machine Learning to Deep Learning. It covers Neural Networks, CNNs, RNNs, LSTMs, and Transformers using PyTorch.

---

## 🔵 Phase 1: Deep Learning Foundations (4–6 Weeks)

### 1️⃣ Neural Network Fundamentals

#### Core Concepts
- What is a Neural Network?
- Perceptron
- Activation Functions (ReLU, Sigmoid, Tanh, Softmax)
- Forward Propagation
- Loss Functions (MSE, Cross-Entropy)
- Backpropagation
- Gradient Descent
- Overfitting & Regularization (Dropout, L2)

---

### 2️⃣ Math Behind Deep Learning (Revision)

#### Linear Algebra
- Matrix multiplication
- Dot product
- Vector spaces
- Eigenvalues (basic intuition)

#### Calculus
- Partial derivatives
- Chain rule
- Gradient computation

#### Probability
- Softmax as probability distribution
- Log-likelihood
- Cross-entropy loss

---

## 📚 Learning Resources (Foundations)

### 🎥 YouTube Playlists

- **StatQuest – Neural Networks**  
  https://youtube.com/playlist?list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1

- **3Blue1Brown – Neural Networks**  
  https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi

- **DeepLearning.AI (Andrew Ng)**  
  https://www.deeplearning.ai/

---

### 🎓 Courses

- **Google Deep Learning Crash Course**  
  https://developers.google.com/machine-learning/crash-course/neural-networks

- **Embeddings Module (Google ML Crash Course)**  
  https://developers.google.com/machine-learning/crash-course/embeddings

- **Coursera – Deep Learning Specialization (Andrew Ng)**  
  https://www.coursera.org/specializations/deep-learning

- **Fast.ai – Practical Deep Learning**  
  https://course.fast.ai/

---

## 3️⃣ PyTorch Basics (2–3 Weeks)

Students must learn:

- Working with tensors  
- Autograd (automatic differentiation)  
- Implementing a three-layer neural network  
- Writing a full training loop  
- Model evaluation  
- GPU training  

### 📚 Resources

- **PyTorch Official Tutorials**  
  https://pytorch.org/tutorials/

- **PyTorch Playlist (YouTube)**  
  https://youtube.com/playlist?list=PLKnIA16_Rmvboy8bmDCjwNHgTaYH2puK7

- **PyTorch 60 Minute Blitz**  
  https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html

---

# 🔵 Phase 2: Core Deep Learning Architectures (6–8 Weeks)

---

## 📘 Feed-Forward Neural Networks (FNN / MLP)

### Topics
1. Multi-layer neural networks  
2. Activation functions  
3. Loss functions  
4. Backpropagation  
5. Weight initialization  

### Recommended Resources

- **Neural Networks & Deep Learning (Coursera)**  
  https://www.coursera.org/learn/neural-networks-deep-learning

- **Dive into Deep Learning (Free Book with PyTorch Code)**  
  https://d2l.ai/

---

## 📘 Convolutional Neural Networks (CNN)

### Topics
1. Convolution operation  
2. Filters and Feature maps  
3. Stride and Padding  
4. Pooling layers  
5. CNN architectures  
6. Training CNN in PyTorch  

### Recommended Resources

- **Convolutional Neural Networks (Coursera)**  
  https://www.coursera.org/learn/convolutional-neural-networks

- **Dive into Deep Learning – CNN Chapter**  
  https://d2l.ai/chapter_convolutional-neural-networks/index.html

- **PyTorch CIFAR-10 Tutorial**  
  https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html

- **MNIST CNN Tutorial (DataCamp)**  
  https://www.datacamp.com/tutorial/pytorch-cnn-tutorial

---

## 📘 Recurrent Neural Networks (RNN, LSTM, GRU)

### Topics
1. Sequential data  
2. Vanishing gradient problem  
3. Basic RNN  
4. LSTM  
5. GRU  
6. Next-word prediction  

### Recommended Resources

- **Sequence Models (Coursera)**  
  https://www.coursera.org/learn/nlp-sequence-models

- **Dive into Deep Learning – RNN Chapter**  
  https://d2l.ai/chapter_recurrent-neural-networks/index.html

- **PyTorch NLP Tutorial**  
  https://pytorch.org/tutorials/beginner/nlp/sequence_models_tutorial.html

- **Next Word Prediction using LSTM**  
  https://medium.com/@abhishekjainindore24/session-14-next-word-predictor-using-lstm-in-pytorch-bddd2068a909

---

## 📘 Transformers

### Topics
1. Attention mechanism  
2. Self-attention  
3. Scaled dot-product attention  
4. Multi-head attention  
5. Positional encoding  
6. Encoder–Decoder architecture  
7. Fine-tuning pretrained models  

### Recommended Resources

- **Attention Is All You Need (Original Paper)**  
  https://arxiv.org/abs/1706.03762

- **Dive into Deep Learning – Attention Mechanisms Chapter**  
  https://d2l.ai/chapter_attention-mechanisms/index.html

- **Transformers Explained (Visual Guide)**  
  https://ketanhdoshi.github.io/Transformers-Arch/

- https://blog.londogard.com/posts/2021-02-18-transformers-explained/transformers-explained.html  
- https://medium.com/data-science/transformers-explained-visually-part-1-overview-of-functionality-95a6dd460452  
- https://www.geeksforgeeks.org/nlp/machine-translation-with-transformer-in-python/

---

# 🔵 Phase 3: Mini Projects (Choose Any 2)

---

## 🔹 Option A: Image Classification (CNN)

Dataset: CIFAR-10  
https://www.cs.toronto.edu/~kriz/cifar.html

Deliverables:
- Data preprocessing  
- CNN architecture  
- Training curves  
- Accuracy  
- Confusion matrix  
- Conclusion  

---

## 🔹 Option B: Sentiment Analysis (RNN / LSTM)

Dataset: IMDB Reviews  
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

Deliverables:
- Text preprocessing  
- Tokenization  
- LSTM model  
- F1-score evaluation  
- Error analysis  

---

## 🔹 Option C: Text Summarization (Transformer)

Dataset: CNN/DailyMail  
https://github.com/abisee/cnn-dailymail

Deliverables:
- Fine-tuning pretrained model  
- ROUGE evaluation  
- Generated samples  

---

# 📂 Final Submission Format

Students must submit one well-structured notebook/report including:

1. Problem Statement  
2. Dataset Description  
3. Data Preprocessing  
4. Model Architecture Explanation  
5. Training Loop  
6. Loss Curve Visualization  
7. Evaluation Metrics  
8. Error Analysis  
9. Results Discussion  
10. Final Conclusion (5–10 structured lines)

---

# 🎯 Expected Outcomes

After completing this roadmap, students will be able to:

- Build neural networks from scratch  
- Train CNN, RNN, and LSTM models  
- Understand and implement Transformers  
- Fine-tune pretrained models  
- Write structured DL project reports  
- Apply Deep Learning in internships and M.Tech projects  

---
