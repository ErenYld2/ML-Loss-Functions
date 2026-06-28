# Performance Comparison of Various Loss Functions in Benchmark Datasets

This repository contains the experimental setups, model configurations, and source codes for my master's thesis study. The research systematically evaluates and compares the performance of diverse loss functions across multiple data modalities.

---

## 📊 Project Structure & Modalities

The project is organized into dedicated studies based on data modalities, analyzing various loss functions (e.g., BCE, MSE, Focal Loss, Huber Loss):

* **`ImageDataStudy/`** - Deep learning architectures and experiments on image datasets including **CIFAR-10** and **Fashion-MNIST**.
* **`NLPstudy/`** - Text classification and sentiment analysis benchmarks utilizing the **IMDB** dataset.
* **`TimeDataStudy/`** - Time-series analysis and sequence modeling benchmarks using the **FordA** dataset.
* **`VoiceDataStudy/`** - Audio signal processing and classification models trained on the **UrbanSound8K** dataset.
* **`TabularDataStudy/`** - Machine learning benchmarks and regression analysis optimized for tabular data structures.

---

## 💾 Dataset Access (External Storage)

Due to GitHub's file size limitations ($<100\text{ MB}$ per file), the raw datasets and heavy benchmark files used in this thesis are hosted externally on Google Drive. 

You can access and download the full dataset directory directly via the official project link below:

👉 **[Download Project Datasets from Google Drive (Official Link)](https://drive.google.com/drive/folders/1qkwrq0JA5171WIxMM1zdPBeYjzUARhbE?usp=sharing)**

### 🛠️ Setup Instructions
1. Clone this repository to your local machine.
2. Download the respective dataset folders from the Google Drive link directly into their corresponding project directories (`ImageDataStudy/`, `VoiceDataStudy/`, etc.).
3. Ensure all paths in the Jupyter Notebooks (`.ipynb`) align with your local dataset structure.

---

## 🚀 Technical Stack & Frameworks

* **Language:** Python
* **Deep Learning Framework:** PyTorch
* **Machine Learning Tools:** Scikit-learn, Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
