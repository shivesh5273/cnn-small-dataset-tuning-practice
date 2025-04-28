# CNN Small Dataset Tuning Practice

This project focuses on training Convolutional Neural Networks (CNNs) on small datasets and exploring regularization, image augmentation, transfer learning, and fine-tuning.

---

## 🔍 Project Breakdown

### 🐕 1. CNN with L1 Regularization
- Added L1 regularizer (λ = 0.0001) on Dense(512,1) layer.
- Compared model overfitting behavior with vs. without regularization.

### 🖼️ 2. Image Augmentation
- Applied one transformation at a time:
  - Rotation
  - Width Shift
  - Shear
  - Zoom
  - Horizontal Flip
  - Vertical Flip

### 🧠 3. Transfer Learning + Custom Conv Layer
- Extended Dense classifier with an additional Conv layer before Flatten.
- Compared performance against baseline transfer learning approach.

### 🎨 4. Fine-Tuning VGG16
- Fine-tuned only `block4_conv3` while freezing `block5` layers.
- Compared trainable parameters and performance vs. standard fine-tuning.

---

## 📁 Files Included

- `cnn-small-data-problem1-l1-regularization.html`
- `cnn-small-data-problem2-image-augmentation.html`
- `cnn-small-data-problem3-transfer-learning.html`
- `cnn-small-data-problem4-vgg16-finetuning.html`
- `cnn-small-data-overview.docx`

---

## 🛠 Tools Used

- Python 3.x
- TensorFlow / Keras
- OpenCV
- Matplotlib
- Jupyter Notebook

---

> Reinforcing CNN regularization, augmentation, and transfer learning strategies through small dataset experiments.
