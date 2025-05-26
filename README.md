# Biomechanical Movement Classification Using IMU Sensors and Machine Learning

A machine learning system that classifies lower body exercises using data from 6 IMU sensors, implementing four different ML models to analyze biomechanical movement patterns.

## 📌 Project Overview

### Research Question
**Can machine learning correctly classify lower body movements based on 3D acceleration sensor readings?**

### Key Achievements
- Implemented 4 ML models (SVM, Naive Bayes, RNN, KNN) for movement classification
- Achieved up to 100% accuracy on test data
- Developed a comprehensive sensor data processing pipeline
- Identified optimal sensor placements for movement analysis

## 📊 Dataset & Methodology

### Sensor Configuration
- 6 IMU sensors (3 per lower extremity)
- 40Hz sampling rate
- 3D acceleration data (x, y, z planes)

### Exercises Classified
1. Standing
2. Squats
3. Right split squats
4. Left split squats
5. Right lateral lunges
6. Left lateral lunges

### Data Collection
- 8 participants
- Minimum 6 repetitions per exercise
- 12,507 total records

## 🧠 Machine Learning Models

| Model | Accuracy | Key Strengths | Limitations |
|-------|----------|---------------|-------------|
| **Support Vector Machine** | 97% | Excellent for small datasets, effective feature comparison | Limited scalability |
| **Naive Bayes** | 99.36% | Probabilistic approach, handles patterns well | Potential overfitting concerns |
| **Recurrent Neural Network** | 100% | Captures temporal dependencies | Requires more data, overfitting risk |
| **K-Nearest Neighbors** | - | No assumptions about data | Less optimal for known movement patterns |


## 🛠️ Implementation Highlights

### Key Technical Challenges
- Sensor data synchronization
- 3D movement pattern extraction
- Temporal dependency handling
- Overfitting prevention

### Innovative Solutions
- Custom feature comparison framework
- Probabilistic movement pattern analysis
- Cross-validation techniques
- Sensor fusion approaches

## 📈 Results & Findings

1. **Optimal Sensor Placement**: Hip sensors provided most discriminative data for squat classification
2. **Movement Patterns**: Significant correlations found between joint angles and exercise types
3. **Model Selection**: Naive Bayes chosen as optimal balance of accuracy and generalizability
4. **Biomechanical Insights**: Contralateral relationships identified between limb movements

## 📚 References
1. Moniruzzaman, M. (2023). Human walking reconstruction using IMU sensors
2. Hallaj et al (2018). Machine learning in human movement biomechanics
3. Nazarahari & Rouhani (2019). Sensor calibration techniques
- 10+ additional cited papers (see full report)

## 🤝 Contributors
- Ian Abeyta (Data Collection, SVM Implementation)
- Paula Nunez Blazquez (Naive Bayes Model)
- Sushma Kummari (RNN Development)
- Teja Mandaloju (KNN Analysis)
