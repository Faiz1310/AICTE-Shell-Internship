# **Waste Management using Deep Learning: AICTE & SHELL Internship**

**Intern Name:** Mohammad Faizan S  
**Duration:** 4-weeks internship presented by Edunet Foundation, in collaboration with AICTE & Shell  
**Focus:** Green Skills using AI technologies

---

## 1. Introduction
Waste management is one of the biggest challenges faced by urban areas worldwide. Traditional methods of segregation rely on manual labor, which is time-consuming, error-prone, and hazardous. Integrating Deep Learning and Computer Vision provides an automated way to detect and classify waste for efficient recycling and disposal.

## 2. Problem Statement
- Increasing urbanization leads to massive rises in solid waste generation.
- Lack of proper segregation results in pollution, health hazards, and ineffective recycling.
- Manual sorting is inefficient, inconsistent, and unsafe.
- **Goal:** Build an automated waste detection and classification system using Deep Learning.

## 3. Objectives & Scope
- Build a DL-based image classification model for waste detection.
- Categories: Plastic, Metal, Glass, Organic, Paper, E-Waste.
- Develop a real-time system for smart bins or conveyor belts.
- Provide a dashboard for monitoring segregation efficiency.

## 4. Literature Review
- CNN-based waste classification models (ResNet, VGG, MobileNet) show >85% accuracy on public datasets.
- Smart city projects piloting AI-enabled bins.
- Limitations include dataset imbalance, lighting variations, image occlusion.

## 5. Proposed Methodology
- **Dataset:** TrashNet (2500+ images), data augmentation techniques.
- **Preprocessing:** Image resizing, normalization, label encoding.
- **Model:** Convolutional Neural Network or Transfer Learning (ResNet50, MobileNetV2).
- **Training:** 70% train, 20% validation, 10% test; Adam optimizer; Categorical Crossentropy loss; 30–50 epochs.
- **Evaluation:** Accuracy, Precision, Recall, F1-score, Confusion Matrix.

## 6. System Design & Workflow
- **Input:** Waste image captured via camera.
- **Processing:** Deep Learning classifier.
- **Output:** Waste category (e.g., Plastic → Blue Bin).

## 7. Implementation
- **Framework:** TensorFlow/Keras or PyTorch.
- **Hardware:** GPU system (Google Colab, Jetson Nano).
- **Steps:** 
  1. Load & preprocess dataset
  2. Augment data
  3. Train CNN model
  4. Evaluate
  5. Deploy (Flask/Django), dashboard

## 8. Results & Analysis
- **Expected Accuracy:** 85–92% (with Transfer Learning).
- **Example:**
  - Input: Banana peel → Output: Organic Waste
  - Input: Glass bottle → Output: Glass Waste
- Confusion matrix will be reported as part of weekly updates.

## 9. Applications & Impact
- Smart Bins for automatic sorting.
- Efficiency boost in recycling plants.
- Environmental benefits.
- Public health improvements.

## 10. Future Work
- Expand waste categories (hazardous, medical, etc.).
- Integrate IoT sensors for real-time monitoring.
- Deploy on edge devices.
- Enhance model explainability.

## 11. Conclusion
This project showcases how Deep Learning automates waste detection and classification for smarter management and sustainability. Scalable for cities and industries.

## 12. References
- [TrashNet Dataset](https://github.com/garythung/trashnet)
- K. He et al., Deep Residual Learning for Image Recognition, CVPR 2016.
- Other relevant academic literature on CNNs for waste classification.

---

## Weekly Report Instructions
- Create progress logs in folders: **Week1**, **Week2**, **Week3**, **Week4**
- Each week, add program files, results, analysis, and your reflections in the respective folder.
- Update this README and your folder contents as your project advances.