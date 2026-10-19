# AI Polymer Classification

Machine learning project for polymer identification using FTIR spectral data.

The goal of this project is to classify polymers based on their Fourier Transform Infrared (FTIR) spectra and compare the performance of multiple machine learning and deep learning approaches. The FTIR spectra used in this project were obtained from the Kaggle dataset "FTIR Plastic C4" by nhlich2003.

## Models evaluated

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- XGBoost
- Multi-Layer Perceptron (MLP)
- 1D Convolutional Neural Network (1D-CNN)

## Dataset

The dataset contains FTIR spectra of common polymer types, including:

- Polyethylene (PE)
- Polypropylene (PP)
- Polyethylene terephthalate (PET)
- Polystyrene (PS)
- Polyvinyl chloride (PVC)

## Workflow

1. Data preprocessing
   - Baseline correction
   - Spectral normalization
   - Feature scaling

2. Model development
   - Hyperparameter optimization
   - Cross-validation
   - Performance evaluation

3. Model comparison
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion matrix

## Results

| Model | Accuracy |
|---------|---------|
| Logistic Regression | TBD |
| SVM | TBD |
| Random Forest | TBD |
| XGBoost | TBD |
| MLP | TBD |
| 1D-CNN | TBD |

## Technologies

- Python
- Scikit-learn
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Future Work

- Detection of recycled plastics
- Mixed plastic classification
- Real-time FTIR sensor integration
- Chemometric methods (PCA, PLS-