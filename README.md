# ☁️ Weather Classification from Images using Deep Learning

**Course:** FET312 – Deep Learning  
**Semester:** Fall 2025–2026  

---

### 👥 Team DevDL

| Name | Student ID | Model Focus |
| :--- | :--- | :--- |
| **Mehmet Oytun Özer** | 23040301043 | VGG16, MobileNetV2 |
| **Furkan Işık** | 23040301063 | ResNet50, InceptionV3 |
| **Ram Ismail** | 24040301052 | EfficientNetB0, EfficientNetB4 |
| **Muhammet Ay** | 23040301137 | DenseNet121, RegNetX-8GF |

---

## 🌤️ About the Project

In this project, we explored a simple but fascinating question:  
**Can a computer understand the weather just by looking at a photo?**

Instead of using traditional weather sensors or data from weather stations, we relied only on image data. Our aim was to train deep learning models capable of recognizing four different weather conditions:

* ☀️ **Sunny**
* 🌧️ **Rainy**
* ☁️ **Cloudy**
* 🌅 **Sunrise**

We used **Convolutional Neural Networks (CNNs)** together with transfer learning. Training large deep learning models from scratch would require huge datasets and high computational power, which is not practical for a course project. That’s why we used pretrained networks and focused on fine-tuning them and comparing how different architectures perform.

Each team member was responsible for specific models. This allowed us to benchmark **8 different architectures**, and see which ones give the best balance between accuracy and speed.

---

## 🧠 Models We Benchmarked

We experimented with eight state-of-the-art CNN architectures to compare lightweight and heavyweight models:

| Model | Type | Strength |
| :--- | :--- | :--- |
| **MobileNetV2** | Lightweight | Fast inference, suitable for mobile and edge devices |
| **VGG16** | Heavyweight | Strong deep feature extraction, classic architecture |
| **ResNet50** | Standard | Residual connections help prevent vanishing gradients |
| **InceptionV3** | Specialized | Multi-scale processing with wider network structure |
| **EfficientNetB0** | Efficient | Optimized balance between speed and accuracy |
| **EfficientNetB4** | Heavyweight | High accuracy but computationally expensive |
| **DenseNet121** | Complex | Dense connections allow feature reuse |
| **RegNetX-8GF** | Modern | Designed through optimized network design search |

---

## 🛠 Tools & Technologies

We developed the project using the following tools:

* **Programming Language:** Python 3.x
* **Deep Learning Frameworks:** PyTorch / TensorFlow
* **Data Processing:** NumPy, Pandas
* **Visualization:** Matplotlib, Seaborn
* **Evaluation Metrics:** Scikit-learn (Confusion Matrix, F1-Score)

---

## 📊 Evaluation Metrics

To compare the models fairly, we evaluated them using multiple metrics:

* **Accuracy:** Measures overall prediction correctness.
* **Precision:** Indicates how reliable the positive predictions are.
* **Recall:** Shows how well the model identifies all samples of a class.
* **F1-Score:** Harmonic mean of Precision and Recall, especially important for imbalanced datasets.

> *During our analysis, we noticed that heavier models such as EfficientNetB4 achieved higher accuracy, while lightweight models like MobileNetV2 still delivered surprisingly good results with much faster inference times.*

---

## 📂 Dataset & Presentation

We used the **Multi-class Weather Dataset** available on Kaggle.

* 🔗 **Dataset:** [Kaggle - Multiclass Weather Dataset](https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset)
* 📺 **Video Presentation:** [Watch on YouTube](https://www.youtube.com/watch?v=qSmodlwP2H8)

[![YouTube](https://img.youtube.com/vi/qSmodlwP2H8/0.jpg)](https://www.youtube.com/watch?v=qSmodlwP2H8)
