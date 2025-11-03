# Week 1 Progress

## Project Introduction

During Week 1, I began my internship project on **Waste Management using Deep Learning**. The objective is to automate waste segregation in urban environments using a deep learning-based image classifier, which can improve efficiency and sustainability compared to manual methods.

## My Activities This Week

### 1. Literature Review and Project Planning
- I reviewed research papers and case studies about deep learning applications in waste management and smart cities.
- I studied successful implementations of CNN architectures (ResNet, VGG, MobileNet) for image recognition tasks in environmental contexts.
- I summarized the strengths and limitations of existing solutions, focusing on dataset challenges (imbalance, image quality, etc.) and model accuracy.

### 2. Exploring Deep Learning Fundamentals
- I revised neural network concepts: layers, neurons, activation functions, backpropagation, loss functions, and optimizers.
- I focused on CNNs including convolution, pooling, dropout, and dense layers.
- I looked into transfer learning strategies—using pre-trained models for higher accuracy with limited data.

### 3. Practical Environment & Tools Setup
- I installed Python, Jupyter Notebook, TensorFlow, and Keras for model development.
- I also set up PyTorch for experimenting with different frameworks.
- I organized my coding workspace and familiarized myself with the required libraries (numpy, pandas, matplotlib).

### 4. Dataset Acquisition and Exploration
- I downloaded and explored the [TrashNet dataset](https://github.com/garythung/trashnet), examining its different waste categories and sample images.
- I identified class distributions and recognized the need for data augmentation (rotation, flip, scaling) to overcome imbalances and improve model robustness.

### 5. Data Preprocessing
- I resized all images to a standard input size suitable for CNNs.
- I normalized pixel values and performed label encoding for classification.
- I split the dataset into training, validation, and testing sets for accurate evaluation.

### 6. Drafting Workflow and Methodology
- Based on my literature review and data exploration, I designed a workflow for the project:
  1. Preprocess and augment data
  2. Build and train a CNN or use transfer learning
  3. Evaluate model performance with appropriate metrics
  4. Prepare for deployment via API or dashboard

### 7. Notes and Challenges
- Noted common challenges: class imbalance, real-world image noise, lighting variations.
- Planned to address these with data augmentation and careful model selection.
- Collected helpful resources for future weeks:
    - [CS231n: Convolutional Neural Networks](http://cs231n.stanford.edu/)
    - [ResNet Paper](https://arxiv.org/abs/1512.03385)
    - TensorFlow and PyTorch official docs

---

## Week 1 Checklist
- [x] Read project brief and clarify requirements.
- [x] Survey relevant literature and existing solutions.
- [x] Download and explore TrashNet dataset.
- [x] Install Python, Jupyter Notebook, TensorFlow/Keras/PyTorch.
- [x] Practice basic image preprocessing & data augmentation.
- [x] Draft planned workflow and models for coming weeks.

---

## Summary

In Week 1, I established the project foundation by researching deep learning for waste management, studying relevant architectures and datasets, setting up my tools, and planning the implementation workflow. Next week, I’ll move forward with model development and initial experimentation.

---

## References

- [TrashNet Dataset](https://github.com/garythung/trashnet)
- [CS231n Vision Course](http://cs231n.stanford.edu/)
- [TensorFlow Documentation](https://www.tensorflow.org/tutorials)
- [Keras Documentation](https://keras.io/guides/)
- [PyTorch Tutorials](https://pytorch.org/tutorials/)
- Research papers on CNN-based waste classification