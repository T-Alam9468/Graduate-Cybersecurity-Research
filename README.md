# Machine Learning-Based Detection of MFA Fatigue Attacks

## Overview
This research project explores the use of machine learning techniques to detect MFA fatigue attacks in push authentication systems. MFA fatigue attacks, also known as push bombing attacks, exploit user behavior by repeatedly sending authentication prompts until a user accidentally approves a malicious login attempt.

The project compares traditional rule-based detection approaches with supervised machine learning models to determine whether behavioral analysis can improve detection accuracy while reducing false positives.

## Research Objective
The primary goal of this project is to evaluate whether machine learning models can more effectively detect MFA fatigue attacks than static threshold-based systems.

## Technologies & Concepts
- Python
- Machine Learning
- Random Forest
- Logistic Regression
- Behavioral Analytics
- Authentication Security
- Anomaly Detection
- Multi-Factor Authentication (MFA)
- Cybersecurity Research
- Data Analysis

## Dataset
A synthetic dataset containing 10,000 authentication sessions was generated to simulate realistic authentication behavior and MFA fatigue attack scenarios.

### Features Included
- Push request frequency
- Average time between requests
- Interval variance
- Geolocation deviation
- Device mismatch
- Time-of-day deviation

## Models Evaluated
### Rule-Based Baseline
Traditional threshold-based detection using authentication request frequency and geolocation anomalies.

### Logistic Regression
Linear supervised learning model used as a baseline machine learning classifier.

### Random Forest
Ensemble machine learning model used to capture nonlinear behavioral patterns in authentication activity.

## Evaluation Metrics
The models were evaluated using:
- Precision
- Recall
- F1-Score
- False Positive Rate (FPR)
- ROC-AUC

## Results
| Model | Precision | Recall | F1-Score | ROC-AUC |
|---|---|---|---|---|
| Rule-Based | 1.00 | 0.52 | 0.68 | 0.76 |
| Logistic Regression | 0.83 | 0.89 | 0.86 | 0.94 |
| Random Forest | 1.00 | 0.88 | 0.94 | 0.95 |

The Random Forest model achieved the strongest overall performance, demonstrating that behavioral analytics and machine learning can significantly improve MFA fatigue attack detection compared to traditional rule-based approaches.

## Key Findings
- Static threshold systems struggle to detect adaptive attack behavior.
- Machine learning models improve recall and overall detection performance.
- Behavioral analysis provides a more adaptive approach to authentication security.
- Random Forest achieved the best balance between detection accuracy and low false positives.

## Future Improvements
- Train models using real-world enterprise authentication logs
- Develop real-time detection capabilities
- Integrate behavioral biometrics
- Explore deep learning approaches for authentication anomaly detection

## Academic Context
This project was completed for:
### CS-GY 6813 — Information Security & Privacy
New York University (NYU)

## Author
Towhid Alam

## Video Presentation
Presentation Link: https://stream.nyu.edu/media/Defeating+MFA+Fatigue+with+Machine+Learning/1_hw37gkoy

## References
- NIST Digital Identity Guidelines
- Research on MFA effectiveness
- Machine learning for anomaly detection
- Behavioral authentication analytics
