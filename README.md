<div align="center">

# 🧠 CNN Architectures Benchmark

![GitHub repo size](https://img.shields.io/github/repo-size/Avijit-Jana/cnn-architectures-benchmark?style=plastic)
![GitHub language count](https://img.shields.io/github/languages/count/Avijit-Jana/cnn-architectures-benchmark?style=plastic)
![GitHub top language](https://img.shields.io/github/languages/top/Avijit-Jana/cnn-architectures-benchmark?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/Avijit-Jana/cnn-architectures-benchmark?color=red\&style=plastic)

</div>

A systematic benchmarking study of **classical and modern Convolutional Neural Network (CNN) architectures** across datasets of increasing visual complexity.

The goal is simple: understand *how architecture choices behave under different data regimes*, and what trade-offs emerge between accuracy, complexity, and generalization.

---

## 🧠 Project Overview

CNN architectures are often compared in isolation or on a single dataset. This project takes a more **comparative and educational approach**.

Multiple CNN families—ranging from early designs to deeper, attention-enhanced networks—are trained and evaluated on datasets that vary in resolution, color depth, and semantic complexity.

The result is a clear, side-by-side view of **where each architecture shines and where it struggles**.

---

## 🧑‍💼 Why This Matters (Practical Relevance)

In real-world computer vision systems, model choice is rarely about raw accuracy alone. This benchmark helps answer practical questions such as:

* Which architectures are overkill for simpler datasets?
* How does depth and skip-connection design affect generalization?
* When does architectural complexity stop paying off?

These insights translate directly to production decisions in areas like document processing, medical imaging, retail vision, and autonomous systems.

---

## 🏗️ Architectures Evaluated

The following CNN architectures are benchmarked:

* **LeNet-5** – Foundational CNN for digit recognition
* **AlexNet** – Early deep CNN enabling large-scale vision
* **GoogLeNet (Inception)** – Multi-scale feature extraction
* **VGGNet** – Depth-focused architecture with uniform design
* **ResNet** – Residual learning with skip connections
* **Xception** – Depthwise separable convolutions
* **SENet** – Channel-wise attention via squeeze-and-excitation

This mix allows comparisons across eras, design philosophies, and computational budgets.

---

## 📁 Dataset Explanation

Three widely used benchmark datasets are selected to progressively increase task difficulty:

* **MNIST**
  Handwritten digits (28×28, grayscale). A sanity-check dataset for basic representation learning.

* **Fashion MNIST (FMNIST)**
  Clothing items with higher intra-class variation, still grayscale and low-resolution.

* **CIFAR-10**
  Natural images (32×32, RGB) across 10 object categories, introducing color and texture complexity.

This progression exposes how architectures scale from simple pattern recognition to richer visual understanding.

---

## 📊 Evaluation Metrics

Models are evaluated using a balanced set of classification metrics:

* **Accuracy** – Overall correctness
* **Precision** – Quality of positive predictions
* **Recall** – Coverage of actual positives
* **F1-Score** – Balance between precision and recall
* **Loss Curves** – Training stability and convergence behavior

Together, these metrics highlight not just *how well* a model performs, but *how* it learns.

---

## 🚩 How to Navigate the Project

* 📘 **Architecture & Training Details**
  [Approach.md](https://github.com/Avijit-Jana/cnn-architectures-benchmark/blob/main/Approach.md)

* 📊 **Final Results & Analysis**
  [Final_Result.md](https://github.com/Avijit-Jana/cnn-architectures-benchmark/blob/main/Final_Result.md)

* ⚙️ **Install Dependencies**

  ```bash
  pip install -r requirements.txt
  ```

These documents provide deeper insight into design choices, experimental setup, and comparative results.

---

<div align="middle">

![Badge](https://img.shields.io/badge/Developed%20By-Avijit_Jana-blueviolet?style=for-the-badge)

</div>
