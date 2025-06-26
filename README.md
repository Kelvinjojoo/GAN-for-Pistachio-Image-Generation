# 🌱 GAN for Pistachio Image Generation

This project uses a **Generative Adversarial Network (GAN)** to synthesize realistic pistachio images. By training a generator and discriminator adversarially, the model learns to create images that closely resemble the original dataset.

---

## 🧠 Project Overview

- Implemented a GAN using TensorFlow/Keras
- Trained on a dataset of pistachio images
- Designed and compared **baseline** and **modified** generator architectures
- Focused on improving image quality and realism, evaluated using **FID**

---

## 🧪 GAN Architecture

- **Generator:** Transposed convolutional layers with batch normalization and ReLU activation
- **Discriminator:** Standard CNN with LeakyReLU activations and dropout
- Loss function: **Binary Crossentropy**
- Evaluated with: **Frechet Inception Distance (FID)**

---

## 📊 Final Evaluation (FID Score)

| Model            | FID Score |
|------------------|-----------|
| Baseline Model   | 89.66     |
| Modified Model   | 78.52     |
| **Improvement**  | **11.14** |

✅ The **modified generator** significantly reduced the FID score, indicating better quality and more realistic generated pistachio images.
