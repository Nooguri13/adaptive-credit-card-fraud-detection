# Adaptive Credit Card Fraud Detection Using Machine Learning and Deep Reinforcement Learning

## Overview
This project presents a comprehensive fraud detection system that combines supervised machine learning classifiers, unsupervised anomaly detection methods, and deep reinforcement learning (Deep Q-Learning).  
The goal is to detect fraudulent credit card transactions dynamically, even as fraud patterns evolve over time.

## Key Components
- **Data Preprocessing**: Handling missing values, applying SMOTE for class balancing, feature scaling.
- **Supervised Models**: Logistic Regression, Random Forest, Extra Trees, XGBoost, and more.
- **Unsupervised Models**: KMeans, Gaussian Mixture Model, Isolation Forest, Local Outlier Factor.
- **Reinforcement Learning**: Q-Table and Deep Q-Learning (DQN) agents for dynamic fraud detection.
- **Evaluation Metrics**: Precision, Recall, F1-Score, and Accuracy for all models.
- **Visualizations**: Comparative analysis of model performances through multiple graphical representations.

## Folder Structure
/Final_IA_1.ipynb # Supervised Models Training /Final_IA_2.ipynb # Unsupervised Models Training /Final_IA_3.ipynb # Reinforcement Learning (Q-Table) /Final_IA_4.ipynb # Deep Q-Learning (DQN) Training /visualization.ipynb # Graphs for Comparative Analysis /dqn_model.pth # Trained DQN model weights /dqn_classification_report.txt # DQN evaluation report


## How to Run
1. Install dependencies:

2. Open each `.ipynb` notebook and run sequentially:
- Train supervised and unsupervised models.
- Train Q-Table agent.
- Train Deep Q-Learning agent.
- Generate evaluation metrics and visualizations.

3. View the saved model report:  
- `dqn_classification_report.txt` contains detailed Precision, Recall, F1-Score for DQN.

4. Visualize performance comparisons in `visualization.ipynb`.

## Results Summary
- **Deep Q-Learning (DQN)** achieved:
- Precision: 0.98
- Recall: 0.95
- F1-Score: 0.97
- Accuracy: 0.99
- DQN outperformed all traditional supervised and unsupervised models.
- Visual analysis confirmed DQN's superior balance between fraud detection rate and minimal false positives.

## Technologies Used
- Python 3.8
- Scikit-Learn
- TensorFlow / Keras
- OpenAI Gym
- Matplotlib

## Citation
If you use this repository or results in your academic work, please cite:
> Nooguri, Sai Rithwik. Adaptive Credit Card Fraud Detection Using Machine Learning and Deep Reinforcement Learning. 2025.

## Author
[Sai Rithwik Nooguri](https://github.com/Nooguri13)  
M.S. in Computer and Information Science, University of North Florida


