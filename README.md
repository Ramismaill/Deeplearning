# ☁️ Weather Classification from Images using Deep Learning

**Course:** FET312 – Deep Learning  
**Semester:** Fall 2025–2026  

### 👥 Team DevDL

| Name | Student ID | Model Focus |
| :--- | :--- | :--- |
| **Mehmet Oytun Özer** | 23040301043 | VGG16, MobileNetV2 |
| **Furkan Işık** | 23040301063 | ResNet50, InceptionV3 |
| **Ram Ismail** | 24040301052 | EfficientNetB0, EfficientNetB4 |
| **Muhammet Ay** | 23040301137 | DenseNet121, RegNetX-8GF |

---

## 🌤️ About the Project

In this project, we tried to answer a simple but interesting question:  
**Can a computer understand the weather just by looking at a photo?**

Instead of using sensors or weather stations, we focused only on image data. The goal was to train deep learning models that can recognize four weather conditions:

* ☀️ **Sunny**
* 🌧️ **Rainy**
* ☁️ **Cloudy**
* 🌅 **Sunrise**

We used **Convolutional Neural Networks (CNNs)** with transfer learning, because training large models from scratch would require much more data and computing power than we have. By using pretrained networks, we could focus more on fine-tuning and comparing performance.

Each team member worked on different model architectures, and we compared results to see which type of network performs best for visual weather recognition.

---

## 🧠 Models We Tested

Instead of relying on a single architecture, we experimented with **eight well-known CNN models**:

* **VGG16**
* **MobileNetV2**
* **ResNet50**
* **InceptionV3**
* **EfficientNetB0**
* **EfficientNetB4**
* **DenseNet121**
* **RegNetX-8GF**

Some models were lightweight and fast (like **MobileNet**), while others were deeper and more complex (like **EfficientNetB4** and **RegNetX**). This helped us understand the trade-off between accuracy and computational cost.

---

## 🛠 Tools & Technologies

We built the project using:
* **Python** for all development
* **PyTorch / TensorFlow** for deep learning
* **NumPy** for data handling
* **Matplotlib** for visualization
* **Scikit-learn** for evaluation metrics

---

## 📊 How We Evaluated the Models

To compare performance fairly, we used several metrics:

* **Accuracy** – overall correctness
* **Precision** – how reliable the model’s positive predictions are
* **Recall** – how well the model detects all examples of a class
* **F1-Score** – balance between precision and recall

These metrics helped us see not just which model is “most correct,” but which one handles class differences better.
