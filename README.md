# 🚗 Car Damage Detection & Prediction (Deep Learning)

## 🌟 Project Overview
This project is an end-to-end Deep Learning solution designed for the automotive and insurance industries. Using Computer Vision, it automates the visual inspection process to detect and classify vehicle damage from images. 

What sets this project apart is the complete **Mads (Model-as-a-Service)** architecture, featuring a robust PyTorch-trained model served via a **FastAPI** backend and an intuitive **Streamlit** frontend.

## 📸 Visual Results & Demo
Seeing the model in action is the best way to understand its performance. Below are the actual outputs from the inference pipeline.

### 🖼️ Sample Model Predictions
| Input Image | Model Prediction | Confidence/Status |
| :--- | :--- | :--- |
| ![Output 1](https://raw.githubusercontent.com/Paragbokare/Car_Damage_Detection_Deep_Learning/main/images/Screenshot_MY_car.png) | **Inference Result** | ✅ Processed |
| ![Output 2](https://raw.githubusercontent.com/Paragbokare/Car_Damage_Detection_Deep_Learning/main/images/Screenshot_front_breakage.png) | **Damage Result** | ✅ Active |

---

## 🚀 Key Features
* **Automated Image Classification:** Accurately distinguishes between damaged and undamaged vehicles.
* **Full Stack ML:** Includes a web application for user uploads and real-time predictions.
* **Production-Ready API:** FastAPI integration for scalable model serving.
* **Hyperparameter Tuning:** Optimized architecture using PyTorch for high accuracy.

## 🛠️ Technology Stack
| Category | Tools & Technologies |
| :--- | :--- |
| **Deep Learning** | **PyTorch**, **Torchvision** |
| **Backend API** | **FastAPI**, Uvicorn |
| **Frontend UI** | **Streamlit** |
| **Data Processing** | **NumPy**, **OpenCV**, Pillow |
| **Visualization** | Matplotlib, Seaborn |



## 🧠 Methodology
1. **Model Training:** Built using a custom CNN architecture in PyTorch, leveraging Max-Pooling and Dropout layers to prevent overfitting.
2. **Preprocessing:** Standardized image transformations (Resizing, Normalization) to ensure consistent input quality.
3. **Deployment:** The model is served via a FastAPI endpoint that handles POST requests containing image data, returning a structured JSON prediction.

## 📁 Repository Structure
* `Car_damage_prediction.ipynb`: The main training pipeline and data augmentation logic.
* `hyperparameter_tunning.ipynb`: Optimization experiments for model performance.
* `app.py`: Streamlit frontend for the user application.
* `fastapi_server/`: Logic for the API-based model serving.
* `save_car_dl.pth`: Serialized PyTorch model weights.
* `images/`: Folder containing app screenshots and inference results.

## 🧑‍💻 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Paragbokare/Car_Damage_Prediction_Deep_Learning.git](https://github.com/Paragbokare/Car_Damage_Prediction_Deep_Learning.git)
