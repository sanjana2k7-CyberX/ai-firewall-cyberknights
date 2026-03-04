
# AI-Driven Next-Generation Firewall (NGFW)

**Team: CYBER KNIGHTS**

## The Problem

Traditional firewalls rely on static rules and known signatures, making them ineffective against zero-day attacks and encrypted malicious traffic. Modern cyber threats require intelligent, adaptive defense systems.

## Our Solution

We built an **AI-powered Next Generation Firewall** that detects threats based on network behavior instead of signatures.

Using machine learning on the **CICIDS 2017 dataset**, our system:

* Detects zero-day attacks using anomaly detection
* Identifies malicious encrypted traffic without decryption
* Assigns a Zero Trust risk score (0–100)
* Automatically decides to **BLOCK, MONITOR, or ALLOW** traffic



## How It Works

1. **Anomaly Detection (Isolation Forest)**
   Learns normal traffic → flags unusual patterns

2. **Encrypted Traffic Classifier (Random Forest)**
   Uses metadata features only (no payload inspection)

3. **Zero Trust Risk Engine**
   Combines multiple signals into a unified risk score

4. **Automated Response Module**
   High Risk → BLOCK
   Medium Risk → MONITOR
   Low Risk → ALLOW


## Impact

* ~99% encrypted traffic classification accuracy
* Detects attacks without needing signatures
* Works even when traffic is encrypted (TLS 1.3)
* Reduces manual security intervention


## Tech Stack

Python • Scikit-learn • Pandas • NumPy • Matplotlib • Google Colab

## References

#Canadian Institute for Cybersecurity.
CICIDS 2017 Intrusion Detection Dataset.
University of New Brunswick.

#Scikit-learn Documentation.
Isolation Forest & Random Forest Classifier.
https://scikit-learn.org

#NIST.
Zero Trust Architecture (SP 800-207).
National Institute of Standards and Technology.

#Kaggle Dataset:
Network Intrusion Dataset (CICIDS 2017 version).
