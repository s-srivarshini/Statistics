## Mixture of Gaussians Model

This directory contains a Jupyter notebook that explores the implementation and application of the Mixture of Gaussians (MoG) model using the Expectation Maximization (EM) algorithm. The project focuses on the analysis of vowel formant frequencies using Peterson and Barney's dataset.

### Installation

To run the notebook, ensure you have the following Python libraries installed:

```bash
pip install numpy
pip install matplotlib
pip install scipy
pip install scikit-learn
pip install pandas
```

### Dataset
The analysis uses Peterson and Barney's dataset of vowel formant frequencies, which includes measurements of the fundamental frequency (F0) and the first three formant frequencies (F1-F3) of sustained English vowels from various speakers. The dataset is loaded from a .npy file, and we specifically focus on F1 and F2 frequencies for our analysis.


### Overview
The project includes the following key components:

- **Data Preparation**: Loading the dataset and extracting relevant features (F1 and F2) and phoneme IDs.
- **Data Visualization**: Plotting F1 and F2 frequencies to visualize the distribution of phonemes.
- **MoG Model Training**: Implementing the Expectation Maximization (EM) algorithm to train MoG models on the dataset. The process involves fitting Gaussian mixture models to represent the distribution of vowel formant frequencies.
- **Model Evaluation**: Classifying phonemes using the Maximum Likelihood (ML) criterion based on the trained MoG models and calculating misclassification error.
- **Singularity Problem Mitigatio**n: Discussing and implementing a method to overcome the singularity problem often encountered in fitting Gaussian mixture models.

### Highlights
- The notebook demonstrates how to preprocess and visualize complex datasets for pattern recognition tasks.
- Through iterative application of the EM algorithm, we illustrate the process of fitting MoG models to real-world data, providing insights into the distribution of vowel formant frequencies.
- The project emphasizes the importance of addressing the singularity problem in Gaussian mixture models and presents a practical solution to ensure robust model training.
