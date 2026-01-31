# CNN Feature Extraction with Pretrained Models

This repository contains three Jupyter notebooks demonstrating **frozen feature extraction** using popular pretrained convolutional neural network (CNN) architectures. The notebooks explore how to leverage pretrained models as fixed feature extractors for downstream image classification tasks.

## 📂 Repository Contents

* **`InceptionV3.ipynb`**
  Uses the InceptionV3 architecture as a frozen feature extractor. The pretrained convolutional base is kept fixed while custom classification layers are trained on top.

* **`GoogleNet.ipynb`**
  Demonstrates feature extraction using the GoogleNet (Inception v1) architecture with frozen weights to evaluate transfer learning performance.

* **`ResNet50.ipynb`**
  Applies ResNet50 for frozen feature extraction, highlighting residual connections and their effectiveness when used with transfer learning.

## 🧠 Key Concepts Covered

* Transfer learning with pretrained CNNs
* Frozen feature extraction vs. full fine-tuning
* Using architectures such as Inception, GoogleNet, and ResNet
* Building and training custom classification heads
* Evaluating model performance

## 🛠️ Requirements

To run the notebooks, you will typically need:

* Python 3.8+
* Jupyter Notebook or JupyterLab
* TensorFlow / Keras (or equivalent deep learning framework)
* NumPy, Matplotlib

Example installation:

```bash
pip install tensorflow numpy matplotlib jupyter
```

## ▶️ How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Launch Jupyter:

   ```bash
   jupyter notebook
   ```
3. Open any notebook (`InceptionV3.ipynb`, `GoogleNet.ipynb`, or `ResNet50.ipynb`) and run the cells sequentially.

## 📊 Notes

* All models use pretrained weights and keep the convolutional layers frozen during training.
* The notebooks are intended for educational and experimental purposes.
* Datasets, hyperparameters, and results may vary depending on your environment and configuration.

## 📜 License

This project is provided for learning and research purposes. Add a license file if you plan to distribute or reuse this work publicly.

---

Feel free to extend these notebooks by experimenting with fine-tuning, different datasets, or additional architectures.
