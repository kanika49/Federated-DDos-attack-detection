# Federated DDoS Attack Detection using Machine Learning

## Project Overview
This project implements a privacy-preserving Distributed Denial-of-Service (DDoS) attack detection system using Federated Learning.  
Multiple simulated clients collaboratively train a global model without sharing raw network traffic data, ensuring data privacy and security.

The project demonstrates the application of Federated Learning for real-world cybersecurity problems using Machine Learning.

---

## Objective
- Detect DDoS attacks with high accuracy
- Preserve user and network data privacy using Federated Learning
- Reduce false positives in intrusion detection systems

---

## Dataset
- CIC-IDS-2017 dataset
- Contains both benign and malicious network traffic flows
- Includes flow-level statistical features such as packet count, flow duration, and protocol metrics

---

## Tools & Technologies
- Python
- PyTorch
- Scikit-learn
- Pandas, NumPy
- Federated Learning (FedAvg)
- SMOTE for class imbalance handling
- Jupyter Notebook

---

## Methodology
1. Preprocessed network traffic data and performed feature scaling
2. Handled class imbalance using SMOTE
3. Partitioned data across multiple simulated federated clients
4. Trained local models independently on each client
5. Aggregated model weights using Federated Averaging (FedAvg)
6. Evaluated the global model on unseen test data

---

## Results & Insights
- Achieved over 99% recall for DDoS attack detection
- Maintained a low false positive rate
- Demonstrated effective learning without sharing raw data between clients

Business Insight:
Federated Learning enables collaborative intrusion detection while maintaining data privacy, making it suitable for distributed and security-sensitive environments.

---

## How to Run
```bash
git clone https://github.com/kanika49/Federated-DDos-attack-detection

