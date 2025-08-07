# ⚡ Power System Fault Detection and Classification

This project presents a machine learning-based approach for detecting and classifying different types of faults in a power distribution system. Using electrical measurements such as voltage and current phasors, the goal is to identify fault conditions accurately and efficiently — a crucial step toward improving the reliability and stability of power grids.

Developed and executed using **IBM Cloud's Jupyter Notebook environment**, the project is fully cloud-compatible, scalable, and suitable for both research and industrial applications.

---

## 🧰 Technologies Used

- **IBM Cloud (Lite Tier)**:  
  Hosted development and execution environment
   using Jupyter Notebooks.

- **Programming Language**:  
  Python

- **Python Libraries**:
  - `pandas`, `numpy` – Data handling and preprocessing
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – Machine learning models and evaluation

---

## 🤖 Machine Learning Models Implemented

A variety of traditional machine learning models were tested and evaluated for fault classification:

- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest Classifier  
- K-Nearest Neighbors (KNN)  
- Naive Bayes

Each model was trained on preprocessed electrical measurements and assessed on its ability to correctly classify different fault types in a multi-class setting.

---

## ✅ Positive Outcomes & Key Findings

- 🚀 **Strong Baseline Models**:  
  The machine learning pipeline established a robust baseline using classical models, successfully capturing trends in power fault data and distinguishing between fault categories.

- 🔍 **Feature Importance Analysis**:  
  Critical variables such as **Voltage** and **Current** were found to be the most influential in predicting fault conditions, aligning well with electrical engineering principles.

- ⚖️ **Balanced Dataset Performance**:  
  The dataset used was evenly distributed across fault classes, ensuring unbiased learning and fair model evaluation.

- 📊 **Multiclass Capability**:  
  The models showed a strong ability to differentiate among multiple fault types, proving the potential of ML even with basic electrical parameters.

- 📈 **Foundation for Future Research**:  
  The results offer a solid launching pad for future work, including time-series modeling, deep learning, or feature extraction from waveform signals.

---

## 🌱 Future Scope

- Integration of **LSTM/CNN** models to capture time-dependent fault behavior
- Extraction of advanced signal features like **harmonic distortion** or **sequence components**
- Real-time deployment of trained models into SCADA or smart grid systems
- Expansion to include more complex or high-voltage fault datasets

---


