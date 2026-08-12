# 💳 Credit Card Fraud Detection and Financial Risk Analysis

A Deep Learning based Credit Card Fraud Detection system using a **Deep Neural Network (DNN)** and an **Autoencoder** to identify potentially fraudulent and anomalous transactions.

The project also generates a combined **Financial Risk Score** and classifies transactions into:

- 🟢 Low Risk
- 🟡 Medium Risk
- 🔴 High Risk

---

## 📌 Project Overview

Credit card fraud is a major problem in the financial industry. Traditional rule-based systems may not be sufficient to identify complex and changing fraud patterns.

This project uses Deep Learning techniques to analyze credit card transactions and identify suspicious behavior.

Two models are used:

1. **Deep Neural Network (DNN)** – supervised fraud classification
2. **Autoencoder** – anomaly detection

The outputs of both models are combined to generate a final financial risk score.

---

## 🎯 Objectives

- Detect fraudulent credit card transactions.
- Handle highly imbalanced transaction data.
- Use Deep Learning for fraud classification.
- Detect unusual transactions using an Autoencoder.
- Calculate a combined financial risk score.
- Classify transactions into Low, Medium, and High Risk.
- Provide an interactive transaction analysis system.

---

## 🏗️ System Architecture

```text
                 Credit Card Transaction Dataset
                              |
                              v
                     Data Preprocessing
                              |
                    +---------+---------+
                    |                   |
                    v                   v
              DNN Classifier       Autoencoder
                    |                   |
                    v                   v
             Fraud Probability   Reconstruction Error
                    |                   |
                    +---------+---------+
                              |
                              v
                       Risk Score
                              |
                              v
                    Risk Classification
                              |
             +----------------+----------------+
             |                |                |
             v                v                v
          LOW RISK       MEDIUM RISK       HIGH RISK
