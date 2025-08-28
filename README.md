# Adversial-attack-and-defense
🛡️ Adversarial Attacks & Defenses on Fashion MNIST
📌 Project Overview

This project explores adversarial robustness in deep learning, focusing on adversarial attacks (FGSM, PGD) and defenses (Mixed Adversarial Training – MAT) using the FashionMNIST dataset.

Adversarial attacks are small, imperceptible perturbations to input data that can mislead deep learning models into making incorrect predictions. This project demonstrates vulnerabilities in CNNs and implements defense strategies to improve resilience.

🚀 Key Features

Dataset: FashionMNIST (60,000 training, 10,000 testing images across 10 classes).

Attacks Implemented:

FGSM (Fast Gradient Sign Method)

PGD (Projected Gradient Descent)

Defense Strategy:

Mixed Adversarial Training (MAT) with 50% clean + 50% adversarial samples.

📊 Results
Model Setting	Accuracy on Clean Data	Accuracy under FGSM	Accuracy under PGD
Baseline CNN	92%	10%	0.008%
With MAT	91%	97%	68%

✅ MAT significantly improves adversarial robustness while maintaining strong performance on clean data.

⚙️ Tools & Technologies

Languages: Python

Frameworks/Libraries: TensorFlow / PyTorch, NumPy, Matplotlib

Techniques: CNN, Adversarial Training, Data Augmentation

📂 Repository Structure
├── Adversarial_AD_CV.ipynb   # Jupyter Notebook with implementation
├── README.md                 # Project documentation
└── /results                  # Plots, accuracy curves, confusion matrices (optional)

📖 Learning Outcomes

Understood adversarial vulnerabilities of deep learning models.

Implemented FGSM & PGD attacks to evaluate CNN robustness.

Designed a defense strategy (MAT) to mitigate adversarial threats.

Gained practical exposure to adversarial ML, model security, and robust training methods
