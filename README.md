# 🚁 UAV Trajectory Prediction under GPS Spoofing Attacks

This project focuses on multi-step UAV trajectory prediction using time-series flight data collected under GPS spoofing conditions.

Deep learning sequence models are used to forecast future UAV positions and evaluated against simple baseline predictors to measure robustness under abnormal trajectory behavior.

---

## 🎯 Objectives

- Predict multi-step future UAV trajectory
- Learn temporal patterns from flight time-series data
- Evaluate model performance under GPS spoofing disturbances
- Compare sequence models with simple baseline methods

---

## 🧠 Models

- LSTM (Long Short-Term Memory)
- Seq2Seq (Encoder–Decoder architecture)

---

## 📊 Evaluation

Models are evaluated based on:

- Prediction accuracy across multiple time steps
- Error metrics (RMSE, MAE)
- Robustness under anomalous trajectory patterns
- Performance across different sequence configurations

---

## 📂 Project Structure

Model/ # Model definitions (LSTM, Seq2Seq architectures)
Training_validation/ # Training scripts and validation experiments
Testing/ # Model evaluation and performance testing


---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- PyTorch / TensorFlow
- Scikit-learn
- Matplotlib

---

## ▶️ How to Run

1. Train model  
2. Validate performance  
3. Run testing pipeline  

(Modify with exact commands if available)

---

## 📈 Future Work

- Transformer-based trajectory prediction
- Real-time prediction pipeline
- Spoofing detection integration
- Deployment as inference service
