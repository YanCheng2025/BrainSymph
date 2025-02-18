# 🎶 EEG-Based Exploration of Emotional Fluctuations in Ethnic Vocal Music Performances

## 🎯 Project Overview

This project investigates the **emotional dynamics** of **ethnic vocal music performances** using **EEG-based quantitative psychology**. Traditional methods in music-induced emotion research often rely on **self-reports** and **observational analyses**, which struggle to capture **real-time emotional fluctuations**.

To address these challenges, we introduce the **Adaptive Music Anxiety Reduction Model (AMARM)**, a framework that combines:

- 🧠 **EEG signal analysis**  
- 🎵 **Quantitative psychological modeling**  
- 🛠️ **Neural ordinary differential equations (NODEs)**  
- 🤖 **Reinforcement learning (RL)**  

**AMARM** models **emotional trajectories** during performances and provides **personalized, real-time interventions** to **reduce performance-related anxiety**.

**🎯 Goal:** Advance **emotion measurement** and **regulation techniques** in **culturally rich musical contexts**.

---

## 🔑 Key Features

- 🧠 **EEG-Based Emotion Tracking**: Real-time monitoring of music-induced emotional fluctuations.  
- 🎵 **Cultural-Specific Emotion Modeling**: Captures emotional patterns specific to **ethnic vocal music**.  
- ⚙️ **Adaptive Anxiety Reduction**: Personalized feedback based on the **AMARM framework**.  
- 🔍 **Explainable AI**: Uses **SHAP** and **LIME** to explain predictions to researchers.  
- 📊 **Real-Time Feedback**: Interactive dashboard for monitoring emotional states during performances.  
- 🌐 **Multimodal Data Fusion**: Integrates **EEG**, **heart rate**, and **self-reports** for comprehensive insights.  

---

## 🧠 Methodology

The **Adaptive Music Anxiety Reduction Model (AMARM)** consists of the following components:

### 1️⃣ **EEG Data Acquisition Module**  
- Collects **EEG signals** using consumer-grade devices like **Muse 2** or **OpenBCI**.  
- Preprocesses signals with **bandpass filtering** and **artifact removal** (e.g., eye blinks).  

### 2️⃣ **Emotional State Modeling**  
- Extracts **frequency-domain features** (e.g., alpha, beta bands) using **short-time Fourier transforms (STFT)**.  
- Applies **neural ordinary differential equations (NODEs)** to model emotional fluctuations over time.  

### 3️⃣ **Adaptive Intervention Engine**  
- Uses **reinforcement learning (RL)** to trigger **personalized interventions** in real-time.  
- Feedback may include **visual cues**, **auditory prompts**, or **relaxation exercises**.  

### 4️⃣ **Explainable Emotion Prediction**  
- Utilizes **SHAP** and **LIME** to explain which features influence emotional states.  
- Generates insights for researchers and musicians.  

---

## ⚙️ Installation Guide

### 🛠️ **Prerequisites**

- Python 3.8+  
- TensorFlow / PyTorch  
- NumPy / SciPy / Pandas  
- MNE-Python (for EEG signal processing)  
- Matplotlib / Plotly  
- SHAP / LIME  

---

### 💾 **Installation Steps**

1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/EEG-Music-Emotion-Analysis.git
    cd EEG-Music-Emotion-Analysis
    ```

2. **Create a Virtual Environment**
    ```bash
    python -m venv venv
    source venv/bin/activate    # Linux/macOS
    .\venv\Scripts\activate     # Windows
    ```

3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Verify Installation**
    ```bash
    python main.py --test
    ```

---

## 🚀 Quickstart Guide

### 1️⃣ **Run Real-Time EEG Monitoring**
```bash
python main.py --mode monitor
