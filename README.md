<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/status-work%20in%20progress-orange"></a>
  <a href="https://colab.research.google.com/"><img src="https://img.shields.io/badge/Made%20with-Colab-blue?logo=googlecolab"></a>
  <a href="http://ufldl.stanford.edu/housenumbers/"><img src="https://img.shields.io/badge/Dataset-SVHN-green"></a>
  <a href="https://github.com/ultralytics/ultralytics"><img src="https://img.shields.io/badge/Model-YOLOv8-red"></a>
</p>

# Adversarial Attacks in Machine Learning  

This repository presents experiments with **adversarial attacks** and basic **defense methods** in image classification models.  
The work was conducted on the **SVHN dataset** using the **YOLOv8 classification model**.  

<p align="center">
  <img width="800" src="https://github.com/user-attachments/assets/54ce16f6-9d21-4385-9dbf-90a40ff5dc75" alt="Example of adversarial attack" />
</p>  

---

## 📌 Project Description  
Machine learning models, especially deep neural networks, are highly vulnerable to adversarial examples.  
This project explores:  

- Implementing **adversarial attacks**:
  - FGSM (Fast Gradient Sign Method)  
  - PGD (Projected Gradient Descent)  
- Testing the **robustness** of a YOLOv8 classifier under these attacks.  
- Applying **basic defenses**, such as adversarial training.  

The goal is to demonstrate how adversarial perturbations can drastically reduce model accuracy and test different strategies to mitigate this effect.  

---
## ⚠️ Limitations & Future Work  

This research is **not perfect** and requires improvements:  
 
- Broader set of adversarial attacks (**CW, DeepFool, AutoAttack or another ones**).  
- More advanced defense methods (e.g., **randomized smoothing, certified defenses**).  
- Cleaner, **production-ready code** and experiments.  

I am aware of these limitations and plan to **continue refining and expanding** this project in the future.  
