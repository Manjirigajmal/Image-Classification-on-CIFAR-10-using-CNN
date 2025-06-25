# 🧠 Image Classification with CNN on CIFAR-10

This project demonstrates how to build a **Convolutional Neural Network (CNN)** to classify images from the **CIFAR-10** dataset into 10 categories using **TensorFlow/Keras**.

---

## 📌 Dataset

The CIFAR-10 dataset consists of:
- 60,000 32x32 color images in 10 classes
- 50,000 training images and 10,000 test images

**Classes:**  
Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

---

## 🧱 Model Architecture

We built a CNN using Keras with the following layers:
- 3 Convolutional layers with increasing filters (32, 64, 128)
- MaxPooling layers after each convolution
- Flatten + Dense (Fully Connected) layers
- Dropout layer to reduce overfitting
- Final softmax layer for classification

---

## 🔁 Model Improvements

We applied the following techniques to improve accuracy:
- ✅ Added additional convolutional layers
- ✅ Used **Data Augmentation** (rotation, flips, shifts)
- ✅ Trained using `ImageDataGenerator` to generalize better

---

## 📊 Results

- **Initial Accuracy:** 67.07%
- **Final Accuracy after tuning:** **76.45%**
- Evaluated using:
  - Classification Report (Precision, Recall, F1-Score)
  - Confusion Matrix
  - Prediction Visualization


---

## 📌 Conclusion

This project shows how basic CNN architectures can be tuned and enhanced to significantly improve classification performance. It highlights the impact of **depth in architecture** and **augmentation techniques** in real-world image recognition tasks.

---

## 💻 How to Run

1. Open the [[Google Colab notebook](https://colab.research.google.com/drive/19MRF_sTRHzy5vdpgfEz73EXuNVMPsSGo?usp=sharing)](#)
2. Run cells step-by-step
3. Explore training, evaluation, and prediction outputs

---



