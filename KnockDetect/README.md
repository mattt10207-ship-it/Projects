Knock Detect

Acoustic Anomaly Detection for Motor & Engine Health

Knock Detect is a Python-based machine learning tool that analyzes acoustic signals and engine audio to assess operational motor health and flag mechanical anomalies—such as bearing failure, unbalance, or engine knock—before catastrophic failure occurs.

---

Features

* Audio Preprocessing: Ingests `.wav` audio files and converts time-domain signals into frequency-domain representations using `librosa`.
* Feature Extraction: Computes key acoustic metrics including Spectral Centroid, RMS Energy, Zero-Crossing Rate, and Mel-Frequency Cepstral Coefficients (MFCCs).
* ML Diagnostics: Trains baseline classifiers (e.g., Random Forest / Support Vector Machines) to distinguish healthy engine audio from abnormal knocking or mechanical friction.
* Modular Architecture: Designed to easily scale from static audio files to deep learning image classifiers (CNNs) and live audio streams.

---

Tech Stack
* Language: Python 3.10+
* Audio Analysis: `librosa`, `soundfile`, `numpy`
* Machine Learning: `scikit-learn`, `matplotlib`
* Workflow & Environment: Git, Python venv

---

Made by Matthew Taylor

