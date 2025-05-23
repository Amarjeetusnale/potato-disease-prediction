# 🥔 Potato Leaf Disease Detection using CNN

## 📌 Problem Statement

Potato is a staple crop worldwide, but its yield is significantly affected by various plant diseases.  
Manual identification of these diseases is time-consuming, error-prone, and requires agricultural expertise.  
There is a need for an automated, accurate, and scalable solution to detect potato plant diseases early and efficiently.

---

## 💡 Proposed Solution

This project proposes a **deep learning-based image classification system** that uses **Convolutional Neural Networks (CNN)** to detect and classify diseases in potato leaves.  
The model identifies three classes:

- Healthy potato leaves  
- Early blight  
- Late blight  

The system is deployed via a **web interface** where users can upload images of potato leaves and receive a disease classification.

---

## 🛠 System Development Approach

- **Frontend**: HTML (`index.html`)  
- **Backend**: Python with Flask (`app.py`)  
- **Model**: CNN built using TensorFlow/Keras  
- **Dataset**: Publicly available potato leaf dataset  
- **Deployment**: Local server using Flask  
- **Tools Used**:
  - Jupyter Notebook (for model development)  
  - OpenCV (for image processing)

---

## ⚙️ Algorithm & Deployment

### 🧠 CNN Architecture

- **Input Layer**: Image input (e.g., 256x256x3)  
- **3 Convolutional + MaxPooling Layers**: For feature extraction  
- **Flatten Layer**: To convert the feature map into a vector  
- **Dense Layers**: With ReLU activation  
- **Output Layer**: Softmax activation for 3 classes (Healthy, Early Blight, Late Blight)

### 🚀 Deployment

- The trained model (`model.h5`) is loaded into the Flask app.
- Users upload potato leaf images via the web interface.
- The Flask app runs inference and returns classification results to the user.

---

## ✅ Result

- **Example Output**:
  - Disease Classified: `Late Blight`
  - ![Screenshot 2025-05-09 211444](https://github.com/user-attachments/assets/5229ead9-293b-466c-9d74-480bf0b22923)


---

## 🧾 Conclusion

The CNN-based model accurately classifies potato leaf diseases with high accuracy.  
This system provides a fast, accessible, and reliable method for farmers to identify plant health issues, enabling timely action and minimizing crop losses.

---

## 🔮 Future Scope

- Deploy on cloud platforms (e.g., **Heroku**, **AWS**) for global access  
- Extend classification to more plant diseases and crops  
- Develop a mobile application with real-time detection capability  
- Support regional languages for better usability

---

## 📚 References

- Potato Leaf Disease Dataset (e.g., from Kaggle or other public sources)  
- TensorFlow / Keras Documentation  
- Flask Official Documentation  
- OpenCV Official Docs
