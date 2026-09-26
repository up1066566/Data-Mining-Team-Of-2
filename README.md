# Data-Mining-Team-Of-2

This project focuses on analyzing and classifying human activities using accelerometer sensor data.

## 🛠️ Main Python Libraries
* **Pandas** (Data Manipulation & Preprocessing)
* **Scikit-Learn** (Machine Learning & Evaluation)

---

## 📌 Project Tasks & Methodology

1. **Linear Regression Analysis:** Applied linear regression techniques to identify linear correlations within the sensor data.
2. **Supervised Classification:** Evaluated and compared multiple supervised algorithms:
   * Random Forests
   * Bayesian Networks
   * Neural Networks
3. **Unsupervised Clustering:** Grouped underlying activity patterns using:
   * K-Means
   * Hierarchical Clustering

---

## ⚠️ Model Limitations & Key Takeaways

* **Temporal Dependencies:** The model treats sensor readings as independent data points. Neighboring time-steps (time-series context) were not included in the feature extraction phase, which leaves room for better sequential pattern recognition.
