# 🧠 Image Morph Detection Using Deep Learning

This project explores the use of deep learning architectures to detect **morphed human face images** through reconstruction-based methods. Five different models—**VAE**, **Autoencoder**, **GAN**, **Vision Transformer**, and **Diffusion Model**—were implemented, trained, and evaluated using similarity and perceptual metrics.

## 🔍 Overview

- ✅ Trained on a Kaggle human face dataset (7,219 images)
- ✅ Image resolution: 256×256 (2 images per subject)
- ✅ Trained for 150 epochs with max 20 mins/model (using GPU on Google Colab)
- ✅ 4-phase image outputs per model for visual inspection
- ✅ Evaluation metrics: **MSE**, **MAE**, **SSIM**, **LPIPS**, and **Cosine Similarity**

## 📂 Dataset

- Source: [Kaggle - Human Faces Dataset](#) <!-- Replace '#' with actual link -->
- Preprocessing: resizing, normalization, face alignment

## 📊 Evaluation Metrics

| Metric         | Description                                       |
|----------------|---------------------------------------------------|
| MSE            | Mean Squared Error – pixel-wise reconstruction loss |
| MAE            | Mean Absolute Error – absolute difference per pixel |
| SSIM           | Structural Similarity Index – perceptual similarity |
| LPIPS          | Learned Perceptual Image Patch Similarity         |
| Cosine Similarity | Measures directional similarity in feature space |

## 🛠️ Technology Used

- **Google Colab** – for model execution and GPU training
- **Python** – core programming language
- **TensorFlow / PyTorch** – deep learning frameworks
- **OpenCV, PIL** – image preprocessing and visualization
- **NumPy, Scikit-learn** – numerical computations and metrics
- **Matplotlib, TensorBoard** – output visualization and training tracking

## 📸 Model Outputs

Each model produces a 4-phase reconstructed output of face images to help identify morphing behavior visually and analytically.

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/image-morph-detection.git
