

## 🩺 Pet Disease Diagnosis using CNN

This project adds an **AI-powered image-based diagnosis feature** to a veterinary web application.
It uses a **Convolutional Neural Network (CNN)** trained on pet skin images to automatically detect common diseases such as **Dermatitis, Ringworm, Demodicosis, Fungal Infections, Hypersensitivity**, and **Healthy** skin.

### 🔍 Features

* Upload a pet image and get an instant diagnosis
* Predicts disease type with confidence score
* Provides **first-aid suggestions** for each disease
* Can be integrated into any web app (Flask/FastAPI)

### ⚙️ Workflow

1. Dataset prepared with multiple disease categories
2. Trained a simple CNN model (`pet_disease_simplecnn.pth`) using PyTorch
3. Model predicts disease from uploaded images
4. Display diagnosis, confidence, and first-aid guidance

### 📂 Key Files

* `pet_cnn_train.py` — Train the CNN model
* `pet_diagnosis_test_specific.py` — Test/diagnose any image
* `pet_disease_simplecnn.pth` — Trained model weights


