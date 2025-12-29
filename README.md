<h1>IoT Pulse Oximeter using ESP8266</h1>

A low-cost IoT-based pulse oximeter built using ESP8266 (NodeMCU) and MAX30102 sensor to measure heart rate and SpO₂, with real-time display and cloud monitoring.

<h2>Features</h2>

Real-time Heart Rate & SpO₂ measurement
OLED (SSD1306) display support
Blynk IoT app integration for remote monitoring
Signal acquisition using MAX30102 sensor

<h2>Machine Learning</h2>

Includes PPG_ML_ANALYSIS.ipynb for offline PPG signal analysis
Uses feature extraction & Gaussian Process Regression (GPR)
Estimates Respiration Rate (RR) and improves SpO₂ accuracy from PPG signals

<h2>Tech Stack</h2>

Hardware: ESP8266, MAX30102, OLED
Firmware: Arduino (C/C++)
ML: Python, NumPy, SciPy, Scikit-learn
