Project Overview
Traditional neurological monitoring often requires cumbersome and expensive clinical equipment, limiting accessibility. NeuroHear pioneers a new approach by leveraging electroencephalography (EEG) signals collected from convenient, consumer-friendly earbuds. By applying sophisticated signal processing and machine learning, this project aims to provide an accessible and accurate tool for early detection and continuous monitoring of critical neurological conditions.

This system analyzes subtle patterns in brainwave activity to differentiate between healthy signals and those indicative of Alzheimer's, Parkinson's, or epileptic seizures.

✨ Key Features
Multi-Disease Prediction: Classifies EEG signals to detect signs of Alzheimer's, Parkinson's, and seizures.

Accessible Hardware: Designed to work with data from emerging ear-EEG devices, making monitoring more practical for daily life.

Advanced Signal Processing: Implements robust techniques for noise reduction, feature extraction, and time-frequency analysis of complex EEG data.

High-Accuracy Models: Utilizes tailored machine learning architectures for optimal performance across different conditions.

🔧 Models & Methodology
The core of NeuroHear is its two-pronged modeling approach, optimized for the unique characteristics of different neurological signatures:

Recurrent Neural Network (LSTM) for Neurodegenerative Diseases:

An LSTM (Long Short-Term Memory) network is used to predict Alzheimer's and Parkinson's.

Reasoning: LSTMs excel at capturing temporal dependencies and long-term patterns in time-series data, which is crucial for identifying the slow-evolving brainwave changes associated with these conditions.

Ensemble Learning (Random Forest) for Seizures:

A Random Forest classifier is used for the real-time detection of seizures.

Reasoning: Random Forests are highly effective, computationally efficient, and robust for classifying distinct, often abrupt events like epileptic seizures based on extracted EEG features.

💻 Tech Stack
Programming Language: Python

Machine Learning: Scikit-learn, TensorFlow / PyTorch

Signal Processing: SciPy, MNE-Python, NumPy

Data Handling: Pandas
