# 🫁 XAI for Tuberculosis Detection using Deep Learning

![TB Detection](https://img.shields.io/badge/TB--Detection-DeepLearning-blue?style=flat-square)
![Explainability](https://img.shields.io/badge/XAI-GradCAM%20%7C%20LIME-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

This project presents an **Explainable AI (XAI)**-driven approach to detect **tuberculosis (TB)** from chest X-ray (CXR) images using deep learning architectures including **DenseNet, WideResNet, AlexNet**, and **LeNet**. It also integrates **Grad-CAM** and **LIME** to explain model predictions, enhancing clinical trust and transparency.

---

## 🧠 Project Highlights

- 🔍 **Models Used:** DenseNet, LeNet-5, AlexNet, WideResNet
- 🏥 **Data:** Publicly available TB CXR dataset curated with 1,500 TB-positive and 1,500 normal images (after augmentation)
- 🎯 **Accuracy Achieved:**
  - DenseNet: 99.5%
  - WideResNet: 96.8%
  - LeNet: 97.5%
  - AlexNet: 91.8%
- 🧪 **Explainability:** Used Grad-CAM and LIME to visualize infected lung regions and interpret CNN decisions
- 🖥️ **Environment:** Google Colab (T4 GPU), TensorFlow, Keras

---

## 📁 Dataset

A curated, balanced subset from the open-source CXR TB dataset, preprocessed as follows:

- Resized to 256×256
- Grayscale normalization
- Data augmentation (flipping, rotation) to mitigate class imbalance

---

## ⚙️ Model Architectures

- **DenseNet:** Dense connections for efficient feature reuse
- **WideResNet:** Deeper + wider architecture with residual learning
- **AlexNet:** Pioneering deep CNN with multiple conv+FC layers
- **LeNet-5:** Lightweight, early CNN ideal for mobile deployments

---

## 🔍 Explainability Techniques

- **Grad-CAM:** Highlights regions influencing prediction by visualizing class-specific activation maps.
- **LIME:** Perturbs image regions to determine local feature importance and decision boundary.

<img src="docs/assets/gradcam_lime_example.png" alt="GradCAM and LIME Explanation" width="600"/>

---

## 🧪 Performance Summary

| Model      | Accuracy | Precision | Recall | F1 Score |
|------------|----------|-----------|--------|----------|
| **DenseNet** | 99.5%    | 99.3%     | 99.6%  | 99.5%    |
| **WideResNet** | 96.8%    | 97.0%     | 97.0%  | 97.0%    |
| **LeNet**   | 97.5%    | 98.0%     | 98.0%  | 97.0%    |
| **AlexNet** | 91.8%    | 92.0%     | 92.0%  | 92.0%    |

---

## 🧑‍🔬 Authors

- Prajwal Prasad (BT22CSA043)
- Sharit Vaishnav (BT22CSA042)
- Sahil Bagade (BT22CSA033)
- Harshit Ranjan (BT22CSA029)

Supervised by **Dr. Snehal Shinde**  
Indian Institute of Information Technology, Nagpur

---

## 🚀 Future Work

- Add clinical metadata for multimodal learning
- Test with multi-class disease classification (e.g., TB, COVID-19, Pneumonia)
- Deploy lightweight model on mobile/web for rural TB screening
- Incorporate SHAP, CT modalities, and real-time inference APIs

---

## 📜 License

This project is licensed under the MIT License. Feel free to use, share, and improve!

---

## 📬 Contact

Feel free to reach out via [GitHub Issues](https://github.com/your-repo/issues) or connect with the authors for collaborations.

