# Gesture Recognition Project

A real-time gesture recognition system using **ESP32 + MPU6050 sensor** and **Edge Impulse**.  
The project collects motion data, trains a model with spectral feature extraction and classification, and deploys it to Arduino IDE for live gesture detection.

---

## 🔑 Features
- MPU6050 sensor with ESP32 for motion capture  
- Data forwarding via Edge Impulse CLI  
- Spectral feature extraction + classifier model  
- Real-time gesture classification on ESP32  
- Deployment as Arduino library for easy integration  

---

## 🌍 Applications
- Touchless device control  
- Human-computer interaction  
- IoT and wearable devices  
- Gaming and AR/VR input  
- Assistive technologies  

---

## ⚙️ How It Works
1. **Data Forwarding** – Connect ESP32 with Edge Impulse Data Forwarder.  
2. **Data Acquisition** – Record gestures (up-down, side, rest) with proper labeling.  
3. **Model Training** – Use spectral features + classifier (30 training cycles).  
4. **Testing** – Validate predictions and accuracy in Edge Impulse Studio.  
5. **Deployment** – Export as Arduino library and install in Arduino IDE.  
6. **Live Detection** – Run gesture recognition in real time on ESP32.  

---

## 🚀 Technologies
- ESP32 + MPU6050  
- Edge Impulse  
- Arduino IDE  
- Edge Impulse CLI  

---

## 📂 Repository Structure

Gesture-Recognition-Project/ ├── README.md ├── LICENSE ├── .gitignore ├── requirements.txt ├── source_code/          # Firmware + training/testing scripts ├── deployment/           # Arduino library + deployment examples └── data_forwarder/       # Scripts/configs for data forwarding

## 📜 License
This project is licensed under the [MIT License](LICENSE).


