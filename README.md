# AEGIS: Adaptive Ensemble-based Guard for Intrusion Systems

AEGIS is an advanced Intrusion Detection System (IDS) framework that utilizes ensemble learning and adaptive validation techniques to provide robust network security. The framework combines enhanced feature selection, real-time adaptability, and comprehensive validation methods to maintain high accuracy in detecting network intrusions.

## Features

### Advanced Ensemble Architecture
- Random Forest and Gradient Boosting classifiers
- Adaptive thresholding mechanisms
- Real-time concept drift monitoring
- Temporal-aware feature selection

### High Performance
- 99.97% detection accuracy
- Minimized false positives
- Robust performance across diverse attack scenarios
- Efficient computational resource utilization

### Comprehensive Validation
- Time-based cross-validation
- Threshold sensitivity analysis
- Adversarial testing
- Ensemble diversity management

## Components

### EnhancedIDS (E-IDS)
- Feature selection using multiple strategies:
  - Random Forest Importance
  - Mutual Information
  - Recursive Feature Elimination
- Advanced data preprocessing pipeline
- Robust model architecture with Random Forest ensemble

### ImprovedIDS (I-IDS)
- Multi-modal validation framework
- Adaptive threshold optimization
- Advanced ensemble management
- Real-time concept drift detection

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/AEGIS.git

# Install required packages
pip install -r requirements.txt
```

## Requirements
- Python 3.8+
- NumPy
- Pandas
- Scikit-learn
- Joblib
- Matplotlib
- Seaborn
- imbalanced-learn

## Usage

```python
from aegis import EnhancedIDS, ImprovedIDS

# Initialize the IDS system
enhanced_ids = EnhancedIDS()
improved_ids = ImprovedIDS()

# Train the model
enhanced_ids.train(X_train, y_train)

# Evaluate performance
enhanced_ids.evaluate(X_test, y_test)

# Perform advanced validation
validation_results = improved_ids.time_based_validation(X, y)
threshold_results = improved_ids.threshold_sensitivity_analysis(X, y)
```

## Model Architecture

The system employs a multi-layered approach:

### Data Preprocessing
- Handling missing values
- Feature scaling
- Outlier detection
- Data normalization

### Feature Selection
- Temporal-aware selection
- Multi-strategy approach
- Feature importance ranking

### Model Training
- Ensemble learning
- Adaptive thresholding
- Real-time monitoring

### Validation
- Time-based validation
- Concept drift detection
- Adversarial testing

## Performance Metrics

| Metric | Score |
|--------|-------|
| Accuracy | 99.97% |
| Precision | 1.00 |
| Recall | 1.00 |
| F1-Score | 1.00 |

## Visualization Capabilities

The framework includes various visualization tools:
- Network metrics distribution
- Protocol analysis patterns
- Flow characteristics
- Anomaly patterns
- Feature importance analysis

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.


## Acknowledgments

- CICIDS2017 dataset providers
- Contributors to the scikit-learn library
- Research community in network security

## Contact

- Niharika Prasanna Kumar - niharikaresearch7@gmail.com
- Sarah Rukhmuddin Rajgoli - sarahrajgoli@gmail.com

Project Link: https://github.com/yourusername/AEGIS
