# Network Intrusion Detection System (NIDS)

This project presents a complete machine learning pipeline for detecting network intrusions based on structured traffic data. The goal is to build a reliable intrusion detection system that can distinguish between benign and malicious network activity using supervised learning techniques.
The system processes raw network traffic data, performs preprocessing steps, and then applies multiple classification algorithms to find the most effective one. After evaluating several models, a Random Forest classifier was selected as the best-performing model based on its accuracy.

<br />

## Dataset
The dataset used is a preprocessed version of the NSL-KDD or similar intrusion detection benchmark datasets. It includes network traffic features and corresponding class labels for normal and various types of intrusions.
> Note: Full credit to the original dataset authors. This repository uses adapted/preprocessed versions.

<br />

## References
- [Cynthia Koopman's NIDS ML Repo](https://github.com/CynthiaKoopman/Network-Intrusion-Detection)
- [Pentakota Sirisha’s GCN-based Intrusion Detection](https://www.kaggle.com/code/pentakotasirisha/intrusion-detection-system-with-gcn-model#Visualization)
