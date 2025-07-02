# 🧠 COVID-Pneumonia Chest X-ray Detection with CNN + Grad-CAM

This AI-powered desktop application detects **COVID-19**, **Pneumonia**, or **Normal** conditions from chest X-ray images using a custom-built Convolutional Neural Network (CNN). It includes Grad-CAM visualization and generates detailed PDF reports with medical explanations.

---

## ⚙️ Features

- 🧪 Detects **COVID-19**, **Pneumonia**, or **Normal** from X-ray images  
- 📊 Visualizes Grad-CAM heatmap for interpretability  
- 🖥️ Fully functional **Tkinter GUI**  
- 📄 Generates detailed **PDF reports** with predictions and explanations  
- 🧠 Trained on custom CNN with **focal loss** to handle class imbalance  
- 🔍 Explains *why* a class was predicted with side-by-side comparison  

---

## 🧠 Model Summary

- Input Image Size: `224 x 224`
- Architecture: Custom CNN (No pretrained models)
- Loss Function: Focal Loss
- Final Accuracy: **90%+** on test set
- Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

---

## 🖼️ Sample Screenshots

### 🧪 GUI Preview  
<img src="images/gui.png" alt="GUI Preview" width="700"/>

### 📊 Graph Output  
<img src="images/graph.png" alt="Accuracy/Loss Graphs" width="700"/>

### 📷 Model Predictions  
<img src="images/prediction.png" alt="Predictions Screenshot" width="700"/>

### 🔥 Grad-CAM Heatmap  
<img src="images/gradcam.png" alt="Grad-CAM Heatmap" width="700"/>

### 📄 PDF Report  
<img src="images/report.png" alt="PDF Report Screenshot" width="700"/>

---

## 🚀 How to Run the Project

```bash
# 1. Clone the repo
git clone https://github.com/your-username/covid-xray-detection.git
cd covid-xray-detection

# 2. Install requirements
pip install -r requirements.txt

# 3. Run the GUI
python gui.py
