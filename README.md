<img width="451" alt="image" src="https://github.com/user-attachments/assets/954ca858-b12c-44dd-ada3-3280a2c002e8">
<img width="305" alt="image" src="https://github.com/user-attachments/assets/051c316e-8d07-4af4-9b36-035c87f34bf2">
<img width="476" alt="image" src="https://github.com/user-attachments/assets/c2316e94-6d9b-412c-a976-81c14103c19c">

# 🌱 Crop Weed Prediction

A deep learning–based system for **predicting and classifying crops vs. weeds** to support sustainable agriculture. This project was developed during an **industrial internship with Upskill Campus & The IoT Academy in collaboration with UniConverge Technologies (UCT)**.

---

## 📖 Overview
Weeds significantly impact crop yield, food security, and farming costs. Conventional herbicide-based management often harms the environment and human health.  

This project proposes a **Convolutional Neural Network (CNN)**–based model that distinguishes between **crops and weeds from field imagery**, enabling:
- **Targeted pesticide spraying**
- **Reduced chemical usage**
- **Improved crop productivity**
- **Support for sustainable and organic farming practices**

---

## 🏗️ Project Workflow
### 🔹 High-Level Design
1. **Data Acquisition** – Collecting crop and weed images using cameras/drones.  
2. **Data Preparation** – Image resizing (512×512), normalization, augmentation, and labeling.  
3. **Model Training** – CNN with Conv2D, pooling, batch normalization, and dropout layers.  
4. **Prediction & Evaluation** – Binary classification (crop or weed) with metrics such as accuracy, precision, recall, and F1-score.  

### 🔹 Model Architecture (Low-Level)
- **Input Layer**: 512×512×3 images  
- **Conv2D Layers**: Multiple convolution layers (32 → 128 filters) with ReLU  
- **Batch Normalization + MaxPooling**  
- **Dense Layers**: Fully connected layers (128, 64 units)  
- **Dropout**: Regularization to prevent overfitting  
- **Output Layer**: Sigmoid activation for binary classification  

---

## 📊 Results
- The CNN achieved **promising accuracy** within 10 training epochs.  
- Predictions correctly classified unseen test images as either *crop* or *weed*.  
- Example workflow included both weed and crop image evaluations.  

Performance metrics included:  
- Accuracy  
- Precision 
- Recall
- F1-Score 

---

## 📂 Repository Contents
CropWeedProduction/
├── CropWeedPrediction.ipynb        # Jupyter notebook with preprocessing, model training & testing
├── CropWeedProduction_nidhi_USC_UCT.pdf   # Internship report documenting methodology & results
├── data/                           # (placeholder) raw & processed datasets
├── models/                         # (placeholder) trained models/checkpoints
├── results/                        # (placeholder) accuracy plots & prediction outputs
└── README.md

## 🚀 Getting Started
### Prerequisites
- Python 3.7+
- Jupyter Notebook
- GPU (recommended for training)

### Installation
```bash
# Clone repo
git clone https://github.com/nidhijani179/CropWeedProduction.git
cd CropWeedProduction

# Install dependencies
pip install -r requirements.txt

**Running the Notebook**
jupyter notebook CropWeedPrediction.ipynb

🤝 Acknowledgments

Upskill Campus (USC)
The IoT Academy
UniConverge Technologies Pvt. Ltd. (UCT)
Mentors and team members for their guidance during the internship

