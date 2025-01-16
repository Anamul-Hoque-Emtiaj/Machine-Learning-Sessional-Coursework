# Machine-Learning-Sessional-Coursework
All of my assignments and project code of CSE-472 course.

## Project
### PPISP (Protein-Protein Interaction Sites Prediction)
- **Input Processing**: Separate ProtBERT encoders for ligand and receptor sequences
- **Feature Processing**: Linear projection and layer normalization for both inputs
- **Cross-Attention**: Dual L2R/R2L attention layers for bidirectional interaction learning
- **Output**: Pair-wise feature concatenation followed by MLP for interaction score prediction

## Assignments

### 1. Preprocessing and Feature Engineering
- Implementation of data preprocessing techniques
- Feature engineering methods including one-hot encoding and scaling
- Exploratory data analysis and visualization
- Correlation analysis with heatmaps and feature importance
- Binary classification using Logistic Regression
- Performance evaluation on HR attrition dataset

### 2. Logistic Regression with Bagging and Stacking
- Implementation of Logistic Regression from scratch
- Ensemble methods: Bagging
- Meta-learning: Stacking approach
- Performance evaluation and comparison
- Model performance metrics (accuracy, precision, recall, F1)

### 3. Neural Network 
- Implementation of neural network components from scratch:
  - Dense Layer with forward and backward propagation
  - BatchNormalization for training stability
  - ReLU activation function
  - Dropout for regularization
  - Softmax activation for classification
  - Cross Entropy Loss function
  - Adam Optimizer
- Model save and load functionality
- Training and evaluation on FashionMNIST dataset
- Visualization of training progress and results

### 4. PCA and EM
- Principal Component Analysis implementation
- Expectation-Maximization algorithm
- Dimensionality reduction techniques
- Clustering analysis